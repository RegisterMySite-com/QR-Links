https://qr.registermysite.com
Build a complete, production-ready Cloudflare Agents SDK application called TrendReversion AI Trader.
Core Objective
Create a durable, stateful AI trading agent that implements a hybrid Momentum / Trend-Following + Mean-Reversion strategy. The agent should autonomously analyze markets, detect regimes, generate signals, size positions, manage risk, and (optionally) execute trades. Default mode must be paper trading / simulation only. Real-money trading must require explicit human approval and clear risk controls.
Strategy Specification
1. Momentum / Trend-Following Component
Buy assets showing relative strength or rising prices; sell/short assets showing relative weakness.
Classic signals: multi-timeframe moving-average crossovers (e.g. 20/50/200), breakout of recent highs/lows with volume confirmation, and time-series momentum (past N-day returns ranking).
AI enhancements:
Use Workers AI (or external models via AI Gateway) + simple feature engineering or lightweight models (XGBoost-style logic or small LSTM/transformer approximations where feasible) to filter false positives in noisy data.
Multi-timeframe confluence (1h / 4h / daily).
Cross-asset features (correlation with sector ETF, VIX, or market index).
2. Mean-Reversion Component (Pairs & Statistical Arbitrage)
Identify pairs or small baskets of correlated assets.
Monitor z-score of price spreads / residuals from a simple linear or Kalman-filter style fair-value model.
Enter long the underperformer / short the outperformer when the spread reaches extreme z-scores (e.g. |z| > 2.0), with mean-reversion target back toward zero.
AI enhancements: adaptive thresholds, regime-aware cointegration checks, and dynamic pair selection.
3. Regime Detection & Hybrid Logic (Critical)
Continuously classify market regime: Trending vs Range-bound / Mean-reverting using volatility (ATR or realized vol), ADX-like trend strength, VIX proxy if available, and price structure.
In strong trending regimes → overweight Momentum signals and reduce or disable pure mean-reversion.
In range-bound / low-volatility regimes → overweight Mean-Reversion / pairs trades and reduce momentum exposure.
Dynamically scale overall exposure (0–100%) based on regime confidence and recent strategy performance.
Maintain a small “core” allocation that can still take high-conviction signals from either side.
Technical Architecture (Cloudflare Native)
Use the Cloudflare Agents SDK (agents package) with a Durable Object-backed agent for persistent state, scheduling, and long-running sessions.
Agent class should extend Agent and support:
Real-time WebSocket connections for a live dashboard / chat interface.
Scheduled jobs (cron-like via this.schedule) for periodic market scans (e.g. every 5–15 minutes during market hours).
SQL storage (via Durable Object SQLite) for historical signals, positions, equity curve, pair statistics, and regime history.
Tools the agent must have:
Market data fetcher (abstracted; support Polygon, Alpaca, Yahoo Finance-style free endpoints, or any REST API the user configures via secrets).
Technical indicator calculator (SMA, EMA, RSI, ATR, ADX proxy, z-score, correlation).
Regime classifier.
Signal generator (momentum + mean-reversion).
Position sizer & risk engine.
Paper trade executor (and optional real broker connector behind a feature flag + human approval gate).
Logging & performance metrics (Sharpe proxy, win rate, max drawdown, regime attribution).
Use Workers AI for any lightweight inference or natural-language reasoning about the current market state and agent decisions.
Expose a clean React + Tailwind frontend (or Kumo components if preferred) with:
Live equity curve
Current regime indicator
Open positions & pending signals
Recent trade log with reasoning
Manual override / pause / force-regime controls
Chat interface to ask the agent “Why did you take this trade?” or “What is the current regime?”
Risk Management (Non-Negotiable)
Hard max portfolio heat / daily loss limits.
Per-trade risk as % of equity (default 0.5–1%).
Maximum concurrent positions and correlation-aware limits.
Automatic de-leveraging or full pause if drawdown exceeds threshold.
All real trading actions require human-in-the-loop approval (use Agents SDK approval patterns).
Clear disclaimers in UI and logs: “This is experimental. Past performance is not indicative of future results. Paper trade first.”
Configuration & Extensibility
All key parameters (lookback windows, z-score thresholds, MA periods, risk %, universe of assets, data provider keys) must be configurable via environment variables / agent state / simple admin UI.
Start with a small liquid universe (e.g. major US equities + a few ETFs + optional crypto) that the user can expand.
Support both long-only and long/short modes.
Persist everything needed for auditability and walk-forward analysis.
Deliverables Expected from the Builder
Full project structure using the Agents SDK starter pattern.
Complete server.ts (or equivalent) with the Agent class, tools, scheduling, and state management.
Frontend dashboard + chat.
Clear README with:
How to configure data providers and secrets
How to run in paper mode
How to enable real trading (with warnings)
Explanation of the hybrid strategy logic
Sensible defaults so the agent can start scanning immediately after the user supplies a market data API key.
Observability: structured logs, metrics for regime accuracy and strategy attribution.
Extra Quality Requirements
Code should be TypeScript, well-commented, and follow Cloudflare Agents best practices (Durable Objects, hibernation-friendly, tool approval patterns).
Make the agent explain its reasoning in natural language when asked.
Prefer simplicity and robustness over complex unmaintainable ML models. Use Workers AI where it adds clear value; fall back to classical indicators + lightweight heuristics when needed.
The system must be safe by default (paper trading, circuit breakers, human approval for real money).
Build the entire application end-to-end so a developer can clone, set secrets, and have a working hybrid Momentum + Mean-Reversion AI trading agent running on Cloudflare’s global network.