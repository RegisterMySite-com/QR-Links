{'title': 'Homepage', 'url': 'https://registermysite.com/', 'desc': 'Overview of services, how it works, and value proposition'}
{'title': 'About', 'url': 'https://registermysite.com/about', 'desc': 'Company background and service summary'}
{'title': 'Templates & Tools', 'url': 'https://registermysite.com/templates', 'desc': 'Industry-ready website templates'}
{'title': 'Documentation', 'url': 'https://registermysite.com/docs', 'desc': 'Step-by-step guide to domain search, registration, and setup'}
{'title': 'API Reference', 'url': 'https://registermysite.com/api', 'desc': 'Endpoints for authentication (Google/GitHub) and more'}
{'title': 'Domain & DNS Setup', 'url': 'https://registermysite.com/', 'desc': 'Register or connect domains, configure DNS'}
{'title': 'SEO Optimization', 'url': 'https://registermysite.com/', 'desc': 'Technical SEO, schema markup, local SEO, and more'}
{'title': 'Web Design & Templates', 'url': 'https://registermysite.com/templates', 'desc': 'Responsive, mobile-first, conversion-focused designs'}
{'title': 'Custom Business Email', 'url': 'https://registermysite.com/', 'desc': 'Professional @yourbusiness.com addresses'}
{'title': 'Domain Search Tool', 'url': 'https://registermysite.com/tools/Domain_Search', 'desc': 'Check domain availability'}
{'title': 'Contact / Start Project', 'url': 'https://registermysite.com/', 'desc': 'Reach the team to begin a project'}
<project title="RegisterMySite" summary="RegisterMySite is a web development agency that builds multi-platform online presence for businesses.">RegisterMySite helps local and service-based businesses move from scattered listings to a professional, unified online presence.<core pages><doc title="Homepage" desc="Overview of services, how it works, and value proposition"><!DOCTYPE html>
<html lang="en">
<head>

  <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence</title>
    <meta name="description" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">
    <meta name="title" content="RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <!-- Preconnect to the domain-->
    <link rel="preconnect" href="https://visitor-counter.registermysite.com" crossorigin>
    <!-- Optional: Preload the script for even faster loading -->
    <link rel="preload" href="https://visitor-counter.registermysite.com/widget.js" as="script">
  <!-- Favicons and install icons -->
  <link rel="icon" href="/assets/icons/favicon.ico" sizes="any">
  <link rel="icon" type="image/png" sizes="16x16" href="/assets/icons/favicon-16x16.jpg">
  <link rel="icon" type="image/png" sizes="32x32" href="/assets/icons/favicon-32x32.jpg">
  <link rel="icon" type="image/png" sizes="48x48" href="/assets/icons/favicon-48x48.jpg">
  <link rel="icon" type="image/png" sizes="96x96" href="/assets/icons/favicon-96x96.jpg">
  <link rel="apple-touch-icon" sizes="180x180" href="/assets/icons/apple-touch-icon.jpg">
  <link rel="manifest" href="/assets/manifest.json">

  <!-- Open Graph / Facebook -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://registermysite.com">
  <meta property="og:title" content="RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence">
  <meta property="og:description" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">
  <meta property="og:image" content="https://registermysite.com/assets/og-card.jpg">
  <meta property="og:image:width" content="1200">
  <meta property="og:image:height" content="630">
  <meta property="og:image:alt" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">

  <!-- Twitter -->
  <meta property="twitter:card" content="summary_large_image">
  <meta property="twitter:url" content="https://registermysite.com">
  <meta property="twitter:title" content="RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence">
  <meta property="twitter:description" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">
  <meta property="twitter:image" content="https://registermysite.com/assets/og-card.jpg">

  <!-- Structured data -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "WebApplication",
    "name": "Register My Site",
    "url": "https://registermysite.com",
    "description": "RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.",
    "applicationCategory": "UtilitiesApplication",
    "operatingSystem": "Any (Windows, macOS, Android, iOS, Linux, ChromeOS)",
    "isAccessibleForFree": true,
    "offers": {
      "@type": "Offer",
      "price": "0",
      "priceCurrency": "USD"
    }
  }
  </script>

  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Space+Grotesk:wght@500;600;700&display=swap');

    body {
      font-family: 'Inter', system-ui, sans-serif;
      background: #0a0a0f;
      color: #e2e8f0;
    }

    .section-title {
      font-family: 'Space Grotesk', sans-serif;
    }

    .gradient-text {
      background: linear-gradient(135deg, #60a5fa, #a78bfa, #f472b6);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }

    .card {
      background: rgba(255, 255, 255, 0.03);
      border: 1px solid rgba(255, 255, 255, 0.08);
      transition: border-color 0.2s, background 0.2s;
    }

    .card:hover {
      border-color: rgba(96, 165, 250, 0.28);
      background: rgba(255, 255, 255, 0.045);
    }

    /* Hero background image + overlay */
    .hero {
            background: linear-gradient(rgba(0,123,255,0.88), rgba(0,80,200,0.88)), url('https://uploads.registermysite.com/registermysite.gif?auto=format&fit=crop&w=1920&q=80') center/cover no-repeat;
            color: white;
            text-align: center;
            padding: 160px 20px 120px;
            position: relative;
        }

    .cta-primary {
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: #fff;
      transition: background 0.25s ease, transform 0.2s ease, box-shadow 0.25s ease;
    }

    .cta-primary {
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: #fff;
      transition: background 0.25s ease, transform 0.2s ease, box-shadow 0.25s ease;
    }

    .cta-primary:hover {
      background: linear-gradient(135deg, #22d3ee, #a78bfa);
      transform: translateY(-2px);
      box-shadow: 0 12px 32px rgba(96, 165, 250, 0.35);
    }

    .cta-secondary {
      background: transparent;
      color: #e2e8f0;
      border: 1px solid rgba(255, 255, 255, 0.2);
      transition: background 0.25s ease, border-color 0.25s ease, color 0.25s ease, transform 0.2s ease;
    }

    .cta-secondary:hover {
      background: rgba(96, 165, 250, 0.15);
      border-color: #60a5fa;
      color: #93c5fd;
      transform: translateY(-2px);
    }

    /* Domain search bar */
    .domain-search-wrap {
      display: flex;
      flex-direction: column;
      gap: 0.75rem;
      width: 100%;
      max-width: 36rem;
    }

    @media (min-width: 640px) {
      .domain-search-wrap {
        flex-direction: row;
        align-items: stretch;
      }
    }

    .domain-search-input {
      flex: 1;
      background: rgba(0, 0, 0, 0.55);
      border: 1px solid rgba(255, 255, 255, 0.14);
      color: #e2e8f0;
      border-radius: 12px;
      padding: 0.9rem 1.1rem;
      font-size: 1rem;
      transition: border-color 0.2s, box-shadow 0.2s;
      min-width: 0;
    }

    .domain-search-input:focus {
      outline: none;
      border-color: #60a5fa;
      box-shadow: 0 0 0 3px rgba(96, 165, 250, 0.2);
    }

    .domain-search-input::placeholder {
      color: #64748b;
    }

    .domain-search-btn {
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: #fff;
      border: none;
      border-radius: 12px;
      padding: 0.9rem 1.4rem;
      font-weight: 600;
      font-size: 0.95rem;
      cursor: pointer;
      white-space: nowrap;
      transition: background 0.25s ease, transform 0.2s ease, box-shadow 0.25s ease;
    }

    .domain-search-btn:hover:not(:disabled) {
      background: linear-gradient(135deg, #22d3ee, #a78bfa);
      transform: translateY(-1px);
      box-shadow: 0 10px 28px rgba(96, 165, 250, 0.35);
    }

    .domain-search-btn:disabled {
      opacity: 0.65;
      cursor: wait;
    }

    /* Result modal */
    .domain-modal-backdrop {
      position: fixed;
      inset: 0;
      background: rgba(0, 0, 0, 0.7);
      backdrop-filter: blur(6px);
      z-index: 100;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 1.25rem;
      opacity: 0;
      visibility: hidden;
      transition: opacity 0.2s ease, visibility 0.2s ease;
    }

    .domain-modal-backdrop.open {
      opacity: 1;
      visibility: visible;
    }

    .domain-modal {
      background: #12121a;
      border: 1px solid rgba(255, 255, 255, 0.12);
      border-radius: 1.25rem;
      padding: 1.75rem 1.5rem;
      width: 100%;
      max-width: 26rem;
      box-shadow: 0 24px 64px rgba(0, 0, 0, 0.5);
      transform: translateY(12px);
      transition: transform 0.2s ease;
    }

    .domain-modal-backdrop.open .domain-modal {
      transform: translateY(0);
    }

    /* Mobile menu */
    .mobile-panel {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.35s ease;
    }

    .mobile-panel.open {
      max-height: 640px;
    }

    .mobile-sub {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.3s ease;
    }

    .mobile-sub.open {
      max-height: 280px;
    }

    .nav-link {
      transition: color 0.15s ease;
    }

    .nav-link:hover {
      color: #60a5fa;
    }

    .status-pill {
      display: inline-flex;
      align-items: center;
      gap: 0.35rem;
      font-size: 0.75rem;
      padding: 0.35rem 0.7rem;
      border-radius: 9999px;
      background: rgba(16, 185, 129, 0.12);
      border: 1px solid rgba(16, 185, 129, 0.25);
      color: #6ee7b7;
    }

    .step-num {
      width: 2.25rem;
      height: 2.25rem;
      border-radius: 9999px;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      font-weight: 700;
      font-size: 0.9rem;
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: white;
      flex-shrink: 0;
    }
    .logo-circle {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 36px;          /* tiny size */
  height: 36px;
  border-radius: 50%;   /* makes it a circle */
  overflow: hidden;     /* clips the image to the circle */
  background: white;    /* optional fallback */
  border: 2px solid rgba(255,255,255,0.3);
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}

.logo-circle img {
  width: 100%;
  height: 100%;
  object-fit: cover;    /* fills the circle nicely */
}

.logo-circle:hover {
  transform: scale(1.08);
  box-shadow: 0 0 0 3px rgba(79, 70, 229, 0.3);
}
  </style>
   <!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-GMLQJKKPPP"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-GMLQJKKPPP');
</script>
</head>
<body class="min-h-screen">

  <!-- ========== NAVIGATION ========== -->
  <header class="border-b border-white/10 sticky top-0 z-50 backdrop-blur-xl bg-black/70">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="flex items-center justify-between h-16">
        <!-- Logo -->
        <a href="/" class="flex items-center gap-3 shrink-0">
          <img src="https://uploads.registermysite.com/registermysite.gif" alt="Logo" class="h-10 w-10 rounded-xl object-cover bg-white/20">
        <div>
         <span class="text-2xl font-bold tracking-tight">RegisterMySite</span><span class="text-blue-400">.com</span>
          </div>
        </a>

        <!-- Desktop nav -->
        <nav class="hidden lg:flex items-center gap-7 text-sm font-medium">
          <a href="/services" class="nav-link text-slate-300">Services</a>
          <a href="/pricing" class="nav-link text-slate-300">Pricing</a>
          <div class="relative group">
            <button type="button" class="nav-link text-slate-300 inline-flex items-center gap-1.5">
              Tools <i class="fas fa-chevron-down text-[10px] opacity-70"></i>
            </button>
            <div class="invisible opacity-0 group-hover:visible group-hover:opacity-100 transition-all duration-200 absolute top-full left-0 pt-2 w-56">
              <div class="card rounded-xl py-2 shadow-xl shadow-black/40">
                <a href="/tools/Domain_Search" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">Domain Search</a>
                <a href="/tools/TLDsearch" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">TLD Search</a>
                <a href="/tools/QR_Code" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">QR Code</a>
                <a href="/tools/og-preview" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">OG Preview</a>
                <a href="https://meta-gen.registermysite.com" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">Meta Generator</a>
                <a href="https://email-gen.registermysite.com" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">Email Template Generator</a>
                <a href="https://ai.editor.registermysite.com" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">HTML Website Generator</a>
                <a href="/tools" class="block px-4 py-2.5 text-sm text-blue-400 hover:bg-white/5 border-t border-white/10 mt-1 pt-2.5">All tools →</a>
              </div>
            </div>
          </div>
          <a href="/Web_Design" class="nav-link text-slate-300">Web Design</a>
          <a href="/Business_Email.html" class="nav-link text-slate-300">Business Email</a>
          <a href="/docs" class="nav-link text-slate-300">Docs</a>
          <a href="/contact" class="nav-link text-slate-300">Contact</a>
          <a href="/login" class="cta-primary text-sm font-semibold px-4 py-2 rounded-lg">Login</a>
        </nav>

        <!-- Mobile hamburger -->
        <button type="button" id="menu-btn" class="lg:hidden w-10 h-10 flex items-center justify-center rounded-lg border border-white/10 text-slate-200 hover:border-blue-400/40" aria-label="Open menu" aria-expanded="false">
          <i class="fas fa-bars text-lg" id="menu-icon"></i>
        </button>
      </div>

      <!-- Mobile dropdown panel -->
      <div id="mobile-menu" class="mobile-panel lg:hidden border-t border-white/10">
        <nav class="py-3 flex flex-col text-sm font-medium">
          <a href="/services" class="px-2 py-3 text-slate-300 hover:text-blue-400">Services</a>
          <a href="/pricing" class="px-2 py-3 text-slate-300 hover:text-blue-400">Pricing</a>

          <!-- Expandable: Tools -->
          <button type="button" id="tools-toggle" class="px-2 py-3 text-left text-slate-300 hover:text-blue-400 flex items-center justify-between w-full">
            <span>Tools</span>
            <i class="fas fa-chevron-down text-xs transition-transform duration-200" id="tools-chevron"></i>
          </button>
          <div id="tools-sub" class="mobile-sub bg-black/30 rounded-xl mx-1 mb-1">
            <a href="/tools/Domain_Search" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">Domain Search</a>
            <a href="/tools/TLDsearch" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">TLD Search</a>
            <a href="/tools/QR_Code" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">QR Code Generator</a>
            <a href="/tools/og-image" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">OG Image Generator</a>
            <a href="/tools/og-preview" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">OG Preview</a>
            <a href="https://meta-gen.registermysite.com" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">Meta Title Generator</a>
            <a href="https://email-gen.registermysite.com" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">Email Template Generator</a>
            <a href="https://ai.editor.registermysite.com" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">HTML Website Generator</a>
            <a href="/tools" class="block px-4 py-2.5 text-blue-400 hover:text-blue-300">View all tools →</a>
          </div>

          <a href="/Web_Design" class="px-2 py-3 text-slate-300 hover:text-blue-400">Web Design</a>
          <a href="/SEO_Optimization" class="px-2 py-3 text-slate-300 hover:text-blue-400">SEO</a>
          <a href="/Business_Email" class="px-2 py-3 text-slate-300 hover:text-blue-400">Business Email</a>
          <a href="/docs" class="px-2 py-3 text-slate-300 hover:text-blue-400">Docs</a>
          <a href="/contact" class="px-2 py-3 text-slate-300 hover:text-blue-400">Contact</a>
          <a href="/login" class="mx-2 mt-2 mb-3 cta-primary text-center font-semibold py-3 rounded-xl">Login / Sign up</a>
        </nav>
      </div>
    </div>
  </header>

  <!-- ========== HERO ========== -->
  <section class="hero">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-24 w-full relative z-10">
      <p class="text-blue-400 text-sm font-semibold tracking-wide uppercase mb-4">Web development agency</p>
      <h1 class="section-title text-4xl sm:text-5xl md:text-6xl font-bold leading-tight mb-5 max-w-3xl">
        Your Business <span class="gradient-text">Online</span>
      </h1>
      <p class="text-slate-300 text-lg md:text-xl max-w-2xl leading-relaxed mb-8">
        Multi-platform presence that ties your website, Google Business, Yelp, and social profiles together —
        so customers find a professional brand, not scattered listings.
      </p>

      <form id="hero-domain-form" class="domain-search-wrap mb-4" autocomplete="off">
        <input
          type="text"
          id="hero-domain-input"
          class="domain-search-input"
          placeholder="Search a domain — e.g. example.com"
          spellcheck="false"
          autocapitalize="off"
          inputmode="url"
          aria-label="Domain name to search"
        />
        <button type="submit" id="hero-domain-btn" class="domain-search-btn">
          <i class="fas fa-search mr-1.5"></i> Search
        </button>
      </form>
      <p id="hero-domain-hint" class="text-sm text-slate-500 mb-6 min-h-[1.25rem]"></p>

      <div class="flex flex-col sm:flex-row gap-3 sm:gap-4 mb-10">
        <a href="/contact" class="cta-secondary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl text-base">
          <i class="fas fa-envelope"></i>
          Contact Us Today
        </a>
        <a href="/tools/Domain_Search" class="cta-secondary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl text-base text-sm">
          Advanced domain tools →
        </a>
      </div>

      <!-- Platform status pills -->
      <div class="flex flex-wrap gap-2">
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Yelp · Claimed &amp; Linked</span>
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Google Business · Claimed &amp; Linked</span>
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Facebook · Connected</span>
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Instagram · Connected</span>
      </div>
    </div>
  </section>

  <!-- ========== CORE SERVICES ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-20">
    <div class="text-center mb-12">
      <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
        Everything Your Business Needs <span class="gradient-text">Online</span>
      </h2>
      <p class="text-slate-400 text-base md:text-lg max-w-2xl mx-auto leading-relaxed">
        From domain setup to SEO-powered websites and professional email — we handle the technical side
        so you can focus on customers.
      </p>
    </div>

    <div class="grid sm:grid-cols-2 gap-5">
      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-blue-500/15 text-blue-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-globe"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">Domain &amp; DNS Setup</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          We register or connect your domain, configure DNS records correctly, and make sure everything
          points to your new site with zero downtime.
        </p>
      </article>

      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-violet-500/15 text-violet-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-magnifying-glass"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">SEO Optimization</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Technical SEO, schema markup, local SEO, and strategic linking of all your platform profiles
          so Google ranks your business higher.
        </p>
      </article>

      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-pink-500/15 text-pink-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-palette"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">Web Design &amp; Templates</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Beautiful, conversion-focused designs and ready-to-use industry templates. Fully responsive
          and mobile-first for every device.
        </p>
      </article>

      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-emerald-500/15 text-emerald-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-envelope"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">Custom Business Email</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Professional email addresses (@yourbusiness.com) with auto-reply workers that respond
          instantly while you’re busy with customers.
        </p>
      </article>
    </div>
  </section>

  <!-- ========== HOW IT WORKS ========== -->
  <section class="border-y border-white/5 bg-white/[0.015]">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-20">
      <div class="text-center mb-12">
        <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
          How It <span class="gradient-text">Works</span>
        </h2>
        <p class="text-slate-400 max-w-xl mx-auto">
          From scattered listings to a fully connected online presence in four simple steps.
        </p>
      </div>

      <div class="grid md:grid-cols-2 gap-5">
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">1</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Audit Your Listings</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              We find every unclaimed or disconnected profile for your business across major platforms.
            </p>
          </div>
        </div>
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">2</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Build Your Website</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              Choose a template or go custom. We create a site that showcases your business and services.
            </p>
          </div>
        </div>
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">3</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Claim &amp; Link Everything</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              We claim your Yelp, Google Business, and other accounts and link them back to your new website.
            </p>
          </div>
        </div>
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">4</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Launch &amp; Rank</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              DNS, SEO, emails, and analytics go live. Your business becomes discoverable and professional.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ========== TOOLS ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-20">
    <div class="text-center mb-12">
      <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
        Built for Developers &amp; <span class="gradient-text">Businesses</span>
      </h2>
      <p class="text-slate-400 max-w-xl mx-auto">
        Powerful tools when you need them, simple when you don’t.
      </p>
    </div>

    <div class="grid md:grid-cols-3 gap-5">
      <article class="card rounded-2xl p-6">
        <div class="text-blue-400 text-xl mb-3"><i class="fas fa-file-lines"></i></div>
        <h3 class="font-semibold text-lg mb-2">Templates</h3>
        <p class="text-sm text-slate-400 leading-relaxed mb-4">
          Browse dozens of industry-ready website templates. Restaurants, salons, contractors, clinics —
          pick one and customize in minutes.
        </p>
        <a href="/templates" class="text-sm text-blue-400 hover:text-blue-300 font-medium">Browse templates →</a>
      </article>
      <article class="card rounded-2xl p-6">
        <div class="text-violet-400 text-xl mb-3"><i class="fas fa-bolt"></i></div>
        <h3 class="font-semibold text-lg mb-2">API</h3>
        <p class="text-sm text-slate-400 leading-relaxed mb-4">
          Programmatically manage domains, DNS, listings, and site deployments. Perfect for agencies
          managing multiple client sites.
        </p>
        <a href="/api" class="text-sm text-blue-400 hover:text-blue-300 font-medium">API reference →</a>
      </article>
      <article class="card rounded-2xl p-6">
        <div class="text-pink-400 text-xl mb-3"><i class="fas fa-book"></i></div>
        <h3 class="font-semibold text-lg mb-2">Docs</h3>
        <p class="text-sm text-slate-400 leading-relaxed mb-4">
          Clear documentation for DNS, email workers, SEO best practices, and integrating third-party
          platforms with your site.
        </p>
        <a href="/docs" class="text-sm text-blue-400 hover:text-blue-300 font-medium">Read docs →</a>
      </article>
    </div>
  </section>

  <!-- ========== EXTRA VALUE (LA/OC + ownership) ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 pb-16">
    <div class="grid md:grid-cols-2 gap-5">
      <div class="card rounded-2xl p-6 md:p-8">
        <div class="text-emerald-400 mb-3"><i class="fas fa-map-marker-alt"></i></div>
        <h3 class="section-title text-xl font-bold mb-2">In-person in LA &amp; OC</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Prefer face-to-face? We offer service calls across Los Angeles and Orange County —
          discovery meetings, design reviews, staff training, and on-site help. Remote clients
          are fully supported online.
        </p>
      </div>
      <div class="card rounded-2xl p-6 md:p-8">
        <div class="text-blue-400 mb-3"><i class="fas fa-key"></i></div>
        <h3 class="section-title text-xl font-bold mb-2">You own the code &amp; data</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Built in-house. Source, assets, and deploy config are yours — not locked inside a page builder
          you rent forever. You dream. We code.
        </p>
      </div>
    </div>
  </section>

  <!-- ========== FINAL CTA ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 pb-20">
    <div class="card rounded-3xl p-8 md:p-12 text-center relative overflow-hidden">
      <div class="absolute inset-0 bg-gradient-to-br from-blue-600/10 via-transparent to-violet-600/10 pointer-events-none"></div>
      <div class="relative">
        <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
          Ready to Claim Your Online Presence?
        </h2>
        <p class="text-slate-400 max-w-xl mx-auto mb-8 leading-relaxed">
          Stop losing customers to unclaimed listings. Let’s build the website that ties everything
          together and gets you found.
        </p>
        <div class="flex flex-col sm:flex-row items-center justify-center gap-3 sm:gap-4">
          <a href="/contact" class="cta-primary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl">
            Contact Us Today
          </a>
          <a href="/tools/Domain_Search" class="cta-secondary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl">
            Search a Domain
          </a>
        </div>
      </div>
    </div>
  </section>

<div class="announcement-banner">
  <div class="banner-container">
    <div class="banner-text" id="bannerText"></div>
  </div>
</div>

<style>
.announcement-banner {
  width: 100%;
  height: 45px;
  background: linear-gradient(135deg, #0a0a0f, #0a0a0f);
  color: white;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 24px;
  font-weight: bold;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  position: relative;
  box-shadow: 0 2px 8px rgba(0,0,0,0.2);
  margin: 10px auto;
  border-radius: 4px;
}

.banner-container {
  width: 100%;
  height: 100%;
  position: relative;
}

.banner-text {
  position: absolute;
  width: 100%;
  text-align: center;
  padding: 0 20px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;

  /* Initial state */
  opacity: 0;
  transform: translateX(50px); /* Start slightly to the right */
  transition: all 0.7s cubic-bezier(0.4, 0, 0.2, 1);
}

/* Active state - visible and centered */
.banner-text.active {
  opacity: 1;
  transform: translateX(0);
}

/* Previous slide (for outgoing) */
.banner-text.out {
  opacity: 0;
  transform: translateX(-50px);
}
</style>

<script>
// Messages - edit these freely
const messages = [
  "🤖 Cloudflare AI",
  "GitHub for Version Control",
  "Google Business Claimed & Linked",
  "Facebook Optimization",
  "Rank #1 on Google",
  "Fine Tuned SEO Strategies",
  "Search Engine Optimized",
  "Analytics Engines",
  "Email Tracking Pixels",
  "Click Tracking",
  "Generate Email Templates",
  "Generate Keywords",
  "Generate Meta Tags",
  "Custom Smart AI Bots",
  "Email Automation",
  "Send Custom Emails",
  "Advanced Dashboards",
  "American Made Technology",
  "24/7 Live Developer Support",
  "You own the Source Code",
  "Custom Builds shipped World Wide"
];

let currentIndex = 0;
const bannerText = document.getElementById('bannerText');

function showMessage(index) {
  bannerText.innerHTML = messages[index];
  bannerText.classList.add('active');
}

function nextMessage() {
  const currentText = bannerText;

  // Start outgoing animation
  currentText.classList.add('out');

  setTimeout(() => {
    currentText.classList.remove('active', 'out');

    // Move to next message
    currentIndex = (currentIndex + 1) % messages.length;
    showMessage(currentIndex);
  }, 700); // Match transition duration
}

// Initialize first message
showMessage(0);

// Auto-rotate every 4.2 seconds
setInterval(nextMessage, 4200);
</script>
  <!-- Domain result modal -->
  <div id="domain-modal" class="domain-modal-backdrop" role="dialog" aria-modal="true" aria-labelledby="domain-modal-title" hidden>
    <div class="domain-modal">
      <div class="flex items-start justify-between gap-3 mb-4">
        <div class="flex items-center gap-3">
          <div id="domain-modal-icon" class="w-11 h-11 rounded-xl flex items-center justify-center text-lg bg-emerald-500/15 text-emerald-400">
            <i class="fas fa-check-circle"></i>
          </div>
          <h2 id="domain-modal-title" class="section-title text-xl font-bold">Domain Available!</h2>
        </div>
        <button type="button" id="domain-modal-close" class="text-slate-500 hover:text-white w-9 h-9 rounded-lg hover:bg-white/5" aria-label="Close">
          <i class="fas fa-times"></i>
        </button>
      </div>
      <p id="domain-modal-message" class="text-slate-300 text-sm leading-relaxed mb-6">
        Great news! <strong class="text-white" id="domain-modal-name">example.com</strong> is available for registration.
      </p>
      <div class="flex flex-col sm:flex-row gap-3">
        <a id="domain-modal-register" href="/register" class="cta-primary flex-1 text-center font-semibold py-3 rounded-xl text-sm">
          Register this domain
        </a>
        <button type="button" id="domain-modal-dismiss" class="cta-secondary flex-1 font-semibold py-3 rounded-xl text-sm">
          Search again
        </button>
      </div>
      <p class="text-xs text-slate-500 mt-4 text-center">
        Availability is checked via public DNS and is not a guarantee of registration success.
      </p>
    </div>
  </div>

  <!-- ========== FOOTER ========== -->
  <footer class="border-t border-white/10 py-10">
    <!--=== visitor counter ===-->
      <div id="my-visitor-counter"></div>
<script
  src="https://visitor-counter.registermysite.com/widget.js"
  data-container="my-visitor-counter"
></script>
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="flex flex-col md:flex-row md:items-start justify-between gap-8 mb-8">
        <div>
          <div class="flex items-center gap-2 mb-3">
           <!-- <div class="w-8 h-8 rounded-lg bg-gradient-to-br from-blue-500 to-violet-600 flex items-center justify-center font-bold text-white text-sm">R</div>
            <span class="font-semibold">registermysite.com</span> -->
          </div>
          <p class="text-sm text-slate-500 max-w-xs">Web development for multi-platform business presence. Domains, design, SEO, and email.</br>
          Register your website to start linking your accounts and Rank higher in search results against your competitors. Claim, Link and Rank. </p>
        </div>
        <div class="grid grid-cols-2 sm:grid-cols-3 gap-8 text-sm">
          <div>
            <div class="text-slate-400 font-medium mb-3">Product</div>
            <ul class="space-y-2 text-slate-500">
              <li><a href="/services" class="hover:text-blue-400">Services</a></li>
              <li><a href="/pricing" class="hover:text-blue-400">Pricing</a></li>
              <li><a href="/tools" class="hover:text-blue-400">Tools</a></li>
              <li><a href="/templates" class="hover:text-blue-400">Templates</a></li>
            </ul>
          </div>
          <div>
            <div class="text-slate-400 font-medium mb-3">Company</div>
            <ul class="space-y-2 text-slate-500">
              <li><a href="/docs" class="hover:text-blue-400">Docs</a></li>
              <li><a href="/api" class="hover:text-blue-400">API</a></li>
              <li><a href="/contact" class="hover:text-blue-400">Contact</a></li>
              <li><a href="/login" class="hover:text-blue-400">Login</a></li>
              <li><a href="/sitemap.html" class="hover:text-blue-400">Site Map</a></li>
            </ul>
          </div>
          <div>
            <div class="text-slate-400 font-medium mb-3">Contact</div>
            <ul class="space-y-2 text-slate-500">
              <li><a href="tel:+15627514597" class="hover:text-blue-400">(562) 751-4597</a></li>
              <li><a href="/cdn-cgi/l/email-protection#8be2e5ede4cbf9eeece2f8ffeef9e6f2f8e2ffeea5e8e4e6" class="hover:text-blue-400"><span class="__cf_email__" data-cfemail="afc6c1c9c0efddcac8c6dcdbcaddc2d6dcc6dbca81ccc0c2">[email&#160;protected]</span></a></li>
            </ul>
          <img src="https://uploads.registermysite.com/applist.webp" alt="Venmo, CashApp, Zelle, Paypal payment methods accepted" id="PaymentLogo" style="max-width: 100%; height: auto;">
          </div>
        </div>
      </div>
       <a href="https://x.com/diyregistry" class="logo-circle" title="X.com">
  <img src="https://uploads.registermysite.com/favicon-x.png" alt="X" />
</a>
<a href="https://youtube.com/@RegisterMySite" href="https://www.youtube.com/channel/UCwwGNwZJ5JizhMoFU_Z-WOw" class="logo-circle" title="YouTube">
  <img src="https://uploads.registermysite.com/favicon-youtube.png" alt="YT" />
</a>
<a href="https://yelp.com/RegisterMySite" class="logo-circle" title="yelp">
  <img src="https://uploads.registermysite.com/yelp-icon.png" alt="yelp" />
</a>
<a href="https://www.tiktok.com/@registermysite?_r=1&_t=ZP-98fvlLBUhji" class="logo-circle" title="TikTok">
  <img src="https://uploads.registermysite.com/favicon-tiktok.png" alt="TikTok" />
</a>
<a href="https://instagram.com/RegisterMySite" class="logo-circle" title="InstaGram">
  <img src="https://uploads.registermysite.com/favicon-instagram.png" alt="Instagram" />
</a>
<a href="https://github.com/RegisterMySite-com" class="logo-circle" title="GitHub">
  <img src="https://uploads.registermysite.com/github-icon.jpeg" alt="GitHub" />
</a>
<a href="https://google.registermysite.com/Google-Business-Profile" class="logo-circle" title="Google">
  <img src="https://uploads.registermysite.com/google-icon.jpeg" alt="Google" />
</a>
<a href="https://www.facebook.com/profile.php?id=61592420500053&mibextid=ZbWKwL" class="logo-circle" title="Facebook">
  <img src="https://uploads.registermysite.com/facebook-icon.png" alt="Facebook" />
</a>
                <!-- Logo -->
        <a href="/" class="flex items-center gap-3 shrink-0">
          <div class="flex items-center gap-3">
        <img src="https://uploads.registermysite.com/registermysite.jpg" alt="Logo" class="h-10 w-10 rounded-xl object-cover bg-white/20">

          <div class="leading-tight">
            <span class="text-lg font-bold tracking-tight">RegisterMySite</span><span class="text-blue-400">.com</span>
          </div>
        </a>
            </div>
    </div>
  </footer>
<script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script>
  window.RMS_CHAT = {
    url: "https://ai.registermysite.com",
    title: "RegisterMySite AI",
    position: "right",   // or "left"
    openOnLoad: true,
    buttonLabel: "Chat"
  };
</script>
<script src="https://registermysite.com/ai-chat-widget.js" defer></script>
  <script>
    /* —— Mobile nav —— */
    const menuBtn = document.getElementById('menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');
    const menuIcon = document.getElementById('menu-icon');
    const toolsToggle = document.getElementById('tools-toggle');
    const toolsSub = document.getElementById('tools-sub');
    const toolsChevron = document.getElementById('tools-chevron');

    menuBtn.addEventListener('click', () => {
      const open = mobileMenu.classList.toggle('open');
      menuBtn.setAttribute('aria-expanded', open ? 'true' : 'false');
      menuIcon.className = open ? 'fas fa-times text-lg' : 'fas fa-bars text-lg';
      if (!open) {
        toolsSub.classList.remove('open');
        toolsChevron.style.transform = '';
      }
    });

    toolsToggle.addEventListener('click', () => {
      const open = toolsSub.classList.toggle('open');
      toolsChevron.style.transform = open ? 'rotate(180deg)' : '';
    });

    /* —— Domain search (Google DNS-over-HTTPS, same idea as Domain_Search) —— */
    const form = document.getElementById('hero-domain-form');
    const input = document.getElementById('hero-domain-input');
    const btn = document.getElementById('hero-domain-btn');
    const hint = document.getElementById('hero-domain-hint');
    const modal = document.getElementById('domain-modal');
    const modalTitle = document.getElementById('domain-modal-title');
    const modalMessage = document.getElementById('domain-modal-message');
    const modalName = document.getElementById('domain-modal-name');
    const modalIcon = document.getElementById('domain-modal-icon');
    const modalRegister = document.getElementById('domain-modal-register');
    const modalClose = document.getElementById('domain-modal-close');
    const modalDismiss = document.getElementById('domain-modal-dismiss');

    function normalizeDomain(raw) {
      let d = (raw || '').trim().toLowerCase();
      d = d.replace(/^https?:\/\//, '').replace(/^www\./, '').split('/')[0].split('?')[0];
      return d;
    }

    function isValidDomain(d) {
      return /^[a-z0-9]([a-z0-9-]{0,61}[a-z0-9])?(\.[a-z0-9]([a-z0-9-]{0,61}[a-z0-9])?)+$/i.test(d);
    }

    /** NXDOMAIN / no answers ≈ available; answers present ≈ taken */
    async function checkViaGoogleDNS(domain) {
      const url = `https://dns.google/resolve?name=${encodeURIComponent(domain)}&type=A`;
      const res = await fetch(url, { headers: { Accept: 'application/dns-json' } });
      if (!res.ok) throw new Error('DNS lookup failed');
      const data = await res.json();
      // Status 3 = NXDOMAIN (available). Status 0 with Answer = registered.
      if (data.Status === 3) return { available: true };
      if (data.Status === 0 && data.Answer && data.Answer.length > 0) return { available: false };
      // No answer records often means not resolving (treat as likely available)
      if (data.Status === 0 && (!data.Answer || data.Answer.length === 0)) return { available: true };
      return { available: false };
    }

    function openModal({ available, domain }) {
      modal.hidden = false;
      requestAnimationFrame(() => modal.classList.add('open'));

      if (available) {
        modalTitle.textContent = 'Domain Available!';
        modalIcon.className = 'w-11 h-11 rounded-xl flex items-center justify-center text-lg bg-emerald-500/15 text-emerald-400';
        modalIcon.innerHTML = '<i class="fas fa-check-circle"></i>';
        modalMessage.innerHTML = `Great news! <strong class="text-white" id="domain-modal-name">${escapeHtml(domain)}</strong> is available for registration.`;
        modalRegister.href = `https://registermysite.com/register?domain=${encodeURIComponent(domain)}`;
        modalRegister.style.display = '';
        modalRegister.textContent = 'Register this domain';
      } else {
        modalTitle.textContent = 'Domain Taken';
        modalIcon.className = 'w-11 h-11 rounded-xl flex items-center justify-center text-lg bg-amber-500/15 text-amber-400';
        modalIcon.innerHTML = '<i class="fas fa-times-circle"></i>';
        modalMessage.innerHTML = `<strong class="text-white">${escapeHtml(domain)}</strong> appears to be registered. Try another name or check advanced tools for alternatives.`;
        modalRegister.href = `/tools/Domain_Search`;
        modalRegister.textContent = 'Try advanced search';
      }
    }

    function closeModal() {
      modal.classList.remove('open');
      setTimeout(() => { modal.hidden = true; }, 200);
    }

    function escapeHtml(s) {
      return String(s)
        .replace(/&/g, '&amp;')
        .replace(/</g, '&lt;')
        .replace(/>/g, '&gt;')
        .replace(/"/g, '&quot;');
    }

    form.addEventListener('submit', async (e) => {
      e.preventDefault();
      const domain = normalizeDomain(input.value);
      hint.textContent = '';

      if (!domain) {
        hint.textContent = 'Enter a domain name to search.';
        hint.className = 'text-sm text-amber-400 mb-6 min-h-[1.25rem]';
        return;
      }
      if (!isValidDomain(domain)) {
        hint.textContent = 'Enter a valid domain like example.com';
        hint.className = 'text-sm text-amber-400 mb-6 min-h-[1.25rem]';
        return;
      }

      btn.disabled = true;
      btn.innerHTML = '<i class="fas fa-spinner fa-spin mr-1.5"></i> Checking…';
      hint.textContent = `Checking ${domain}…`;
      hint.className = 'text-sm text-slate-400 mb-6 min-h-[1.25rem]';

      try {
        const result = await checkViaGoogleDNS(domain);
        hint.textContent = '';
        openModal({ available: result.available, domain });
      } catch (err) {
        console.error(err);
        hint.textContent = 'Lookup failed. Please try again or use Domain Search tools.';
        hint.className = 'text-sm text-red-400 mb-6 min-h-[1.25rem]';
      } finally {
        btn.disabled = false;
        btn.innerHTML = '<i class="fas fa-search mr-1.5"></i> Search';
      }
    });

    modalClose.addEventListener('click', closeModal);
    modalDismiss.addEventListener('click', () => {
      closeModal();
      input.focus();
    });
    modal.addEventListener('click', (e) => {
      if (e.target === modal) closeModal();
    });
    document.addEventListener('keydown', (e) => {
      if (e.key === 'Escape' && modal.classList.contains('open')) closeModal();
    });
  </script>
</body>
</html></doc><doc title="About" desc="Company background and service summary"><!DOCTYPE html>
<html lang="en">
<head>

  <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence</title>
    <meta name="description" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">
    <meta name="title" content="RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <!-- Preconnect to the domain-->
    <link rel="preconnect" href="https://visitor-counter.registermysite.com" crossorigin>
    <!-- Optional: Preload the script for even faster loading -->
    <link rel="preload" href="https://visitor-counter.registermysite.com/widget.js" as="script">
  <!-- Favicons and install icons -->
  <link rel="icon" href="/assets/icons/favicon.ico" sizes="any">
  <link rel="icon" type="image/png" sizes="16x16" href="/assets/icons/favicon-16x16.jpg">
  <link rel="icon" type="image/png" sizes="32x32" href="/assets/icons/favicon-32x32.jpg">
  <link rel="icon" type="image/png" sizes="48x48" href="/assets/icons/favicon-48x48.jpg">
  <link rel="icon" type="image/png" sizes="96x96" href="/assets/icons/favicon-96x96.jpg">
  <link rel="apple-touch-icon" sizes="180x180" href="/assets/icons/apple-touch-icon.jpg">
  <link rel="manifest" href="/assets/manifest.json">

  <!-- Open Graph / Facebook -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://registermysite.com">
  <meta property="og:title" content="RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence">
  <meta property="og:description" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">
  <meta property="og:image" content="https://registermysite.com/assets/og-card.jpg">
  <meta property="og:image:width" content="1200">
  <meta property="og:image:height" content="630">
  <meta property="og:image:alt" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">

  <!-- Twitter -->
  <meta property="twitter:card" content="summary_large_image">
  <meta property="twitter:url" content="https://registermysite.com">
  <meta property="twitter:title" content="RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence">
  <meta property="twitter:description" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">
  <meta property="twitter:image" content="https://registermysite.com/assets/og-card.jpg">

  <!-- Structured data -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "WebApplication",
    "name": "Register My Site",
    "url": "https://registermysite.com",
    "description": "RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.",
    "applicationCategory": "UtilitiesApplication",
    "operatingSystem": "Any (Windows, macOS, Android, iOS, Linux, ChromeOS)",
    "isAccessibleForFree": true,
    "offers": {
      "@type": "Offer",
      "price": "0",
      "priceCurrency": "USD"
    }
  }
  </script>

  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Space+Grotesk:wght@500;600;700&display=swap');

    body {
      font-family: 'Inter', system-ui, sans-serif;
      background: #0a0a0f;
      color: #e2e8f0;
    }

    .section-title {
      font-family: 'Space Grotesk', sans-serif;
    }

    .gradient-text {
      background: linear-gradient(135deg, #60a5fa, #a78bfa, #f472b6);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }

    .card {
      background: rgba(255, 255, 255, 0.03);
      border: 1px solid rgba(255, 255, 255, 0.08);
      transition: border-color 0.2s, background 0.2s;
    }

    .card:hover {
      border-color: rgba(96, 165, 250, 0.28);
      background: rgba(255, 255, 255, 0.045);
    }

    /* Hero background image + overlay */
    .hero {
            background: linear-gradient(rgba(0,123,255,0.88), rgba(0,80,200,0.88)), url('https://uploads.registermysite.com/registermysite.gif?auto=format&fit=crop&w=1920&q=80') center/cover no-repeat;
            color: white;
            text-align: center;
            padding: 160px 20px 120px;
            position: relative;
        }

    .cta-primary {
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: #fff;
      transition: background 0.25s ease, transform 0.2s ease, box-shadow 0.25s ease;
    }

    .cta-primary {
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: #fff;
      transition: background 0.25s ease, transform 0.2s ease, box-shadow 0.25s ease;
    }

    .cta-primary:hover {
      background: linear-gradient(135deg, #22d3ee, #a78bfa);
      transform: translateY(-2px);
      box-shadow: 0 12px 32px rgba(96, 165, 250, 0.35);
    }

    .cta-secondary {
      background: transparent;
      color: #e2e8f0;
      border: 1px solid rgba(255, 255, 255, 0.2);
      transition: background 0.25s ease, border-color 0.25s ease, color 0.25s ease, transform 0.2s ease;
    }

    .cta-secondary:hover {
      background: rgba(96, 165, 250, 0.15);
      border-color: #60a5fa;
      color: #93c5fd;
      transform: translateY(-2px);
    }

    /* Domain search bar */
    .domain-search-wrap {
      display: flex;
      flex-direction: column;
      gap: 0.75rem;
      width: 100%;
      max-width: 36rem;
    }

    @media (min-width: 640px) {
      .domain-search-wrap {
        flex-direction: row;
        align-items: stretch;
      }
    }

    .domain-search-input {
      flex: 1;
      background: rgba(0, 0, 0, 0.55);
      border: 1px solid rgba(255, 255, 255, 0.14);
      color: #e2e8f0;
      border-radius: 12px;
      padding: 0.9rem 1.1rem;
      font-size: 1rem;
      transition: border-color 0.2s, box-shadow 0.2s;
      min-width: 0;
    }

    .domain-search-input:focus {
      outline: none;
      border-color: #60a5fa;
      box-shadow: 0 0 0 3px rgba(96, 165, 250, 0.2);
    }

    .domain-search-input::placeholder {
      color: #64748b;
    }

    .domain-search-btn {
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: #fff;
      border: none;
      border-radius: 12px;
      padding: 0.9rem 1.4rem;
      font-weight: 600;
      font-size: 0.95rem;
      cursor: pointer;
      white-space: nowrap;
      transition: background 0.25s ease, transform 0.2s ease, box-shadow 0.25s ease;
    }

    .domain-search-btn:hover:not(:disabled) {
      background: linear-gradient(135deg, #22d3ee, #a78bfa);
      transform: translateY(-1px);
      box-shadow: 0 10px 28px rgba(96, 165, 250, 0.35);
    }

    .domain-search-btn:disabled {
      opacity: 0.65;
      cursor: wait;
    }

    /* Result modal */
    .domain-modal-backdrop {
      position: fixed;
      inset: 0;
      background: rgba(0, 0, 0, 0.7);
      backdrop-filter: blur(6px);
      z-index: 100;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 1.25rem;
      opacity: 0;
      visibility: hidden;
      transition: opacity 0.2s ease, visibility 0.2s ease;
    }

    .domain-modal-backdrop.open {
      opacity: 1;
      visibility: visible;
    }

    .domain-modal {
      background: #12121a;
      border: 1px solid rgba(255, 255, 255, 0.12);
      border-radius: 1.25rem;
      padding: 1.75rem 1.5rem;
      width: 100%;
      max-width: 26rem;
      box-shadow: 0 24px 64px rgba(0, 0, 0, 0.5);
      transform: translateY(12px);
      transition: transform 0.2s ease;
    }

    .domain-modal-backdrop.open .domain-modal {
      transform: translateY(0);
    }

    /* Mobile menu */
    .mobile-panel {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.35s ease;
    }

    .mobile-panel.open {
      max-height: 640px;
    }

    .mobile-sub {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.3s ease;
    }

    .mobile-sub.open {
      max-height: 280px;
    }

    .nav-link {
      transition: color 0.15s ease;
    }

    .nav-link:hover {
      color: #60a5fa;
    }

    .status-pill {
      display: inline-flex;
      align-items: center;
      gap: 0.35rem;
      font-size: 0.75rem;
      padding: 0.35rem 0.7rem;
      border-radius: 9999px;
      background: rgba(16, 185, 129, 0.12);
      border: 1px solid rgba(16, 185, 129, 0.25);
      color: #6ee7b7;
    }

    .step-num {
      width: 2.25rem;
      height: 2.25rem;
      border-radius: 9999px;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      font-weight: 700;
      font-size: 0.9rem;
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: white;
      flex-shrink: 0;
    }
    .logo-circle {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 36px;          /* tiny size */
  height: 36px;
  border-radius: 50%;   /* makes it a circle */
  overflow: hidden;     /* clips the image to the circle */
  background: white;    /* optional fallback */
  border: 2px solid rgba(255,255,255,0.3);
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}

.logo-circle img {
  width: 100%;
  height: 100%;
  object-fit: cover;    /* fills the circle nicely */
}

.logo-circle:hover {
  transform: scale(1.08);
  box-shadow: 0 0 0 3px rgba(79, 70, 229, 0.3);
}
  </style>
   <!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-GMLQJKKPPP"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-GMLQJKKPPP');
</script>
</head>
<body class="min-h-screen">

  <!-- ========== NAVIGATION ========== -->
  <header class="border-b border-white/10 sticky top-0 z-50 backdrop-blur-xl bg-black/70">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="flex items-center justify-between h-16">
        <!-- Logo -->
        <a href="/" class="flex items-center gap-3 shrink-0">
          <img src="https://uploads.registermysite.com/registermysite.gif" alt="Logo" class="h-10 w-10 rounded-xl object-cover bg-white/20">
        <div>
         <span class="text-2xl font-bold tracking-tight">RegisterMySite</span><span class="text-blue-400">.com</span>
          </div>
        </a>

        <!-- Desktop nav -->
        <nav class="hidden lg:flex items-center gap-7 text-sm font-medium">
          <a href="/services" class="nav-link text-slate-300">Services</a>
          <a href="/pricing" class="nav-link text-slate-300">Pricing</a>
          <div class="relative group">
            <button type="button" class="nav-link text-slate-300 inline-flex items-center gap-1.5">
              Tools <i class="fas fa-chevron-down text-[10px] opacity-70"></i>
            </button>
            <div class="invisible opacity-0 group-hover:visible group-hover:opacity-100 transition-all duration-200 absolute top-full left-0 pt-2 w-56">
              <div class="card rounded-xl py-2 shadow-xl shadow-black/40">
                <a href="/tools/Domain_Search" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">Domain Search</a>
                <a href="/tools/TLDsearch" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">TLD Search</a>
                <a href="/tools/QR_Code" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">QR Code</a>
                <a href="/tools/og-preview" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">OG Preview</a>
                <a href="https://meta-gen.registermysite.com" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">Meta Generator</a>
                <a href="https://email-gen.registermysite.com" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">Email Template Generator</a>
                <a href="https://ai.editor.registermysite.com" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">HTML Website Generator</a>
                <a href="/tools" class="block px-4 py-2.5 text-sm text-blue-400 hover:bg-white/5 border-t border-white/10 mt-1 pt-2.5">All tools →</a>
              </div>
            </div>
          </div>
          <a href="/Web_Design" class="nav-link text-slate-300">Web Design</a>
          <a href="/Business_Email.html" class="nav-link text-slate-300">Business Email</a>
          <a href="/docs" class="nav-link text-slate-300">Docs</a>
          <a href="/contact" class="nav-link text-slate-300">Contact</a>
          <a href="/login" class="cta-primary text-sm font-semibold px-4 py-2 rounded-lg">Login</a>
        </nav>

        <!-- Mobile hamburger -->
        <button type="button" id="menu-btn" class="lg:hidden w-10 h-10 flex items-center justify-center rounded-lg border border-white/10 text-slate-200 hover:border-blue-400/40" aria-label="Open menu" aria-expanded="false">
          <i class="fas fa-bars text-lg" id="menu-icon"></i>
        </button>
      </div>

      <!-- Mobile dropdown panel -->
      <div id="mobile-menu" class="mobile-panel lg:hidden border-t border-white/10">
        <nav class="py-3 flex flex-col text-sm font-medium">
          <a href="/services" class="px-2 py-3 text-slate-300 hover:text-blue-400">Services</a>
          <a href="/pricing" class="px-2 py-3 text-slate-300 hover:text-blue-400">Pricing</a>

          <!-- Expandable: Tools -->
          <button type="button" id="tools-toggle" class="px-2 py-3 text-left text-slate-300 hover:text-blue-400 flex items-center justify-between w-full">
            <span>Tools</span>
            <i class="fas fa-chevron-down text-xs transition-transform duration-200" id="tools-chevron"></i>
          </button>
          <div id="tools-sub" class="mobile-sub bg-black/30 rounded-xl mx-1 mb-1">
            <a href="/tools/Domain_Search" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">Domain Search</a>
            <a href="/tools/TLDsearch" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">TLD Search</a>
            <a href="/tools/QR_Code" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">QR Code Generator</a>
            <a href="/tools/og-image" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">OG Image Generator</a>
            <a href="/tools/og-preview" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">OG Preview</a>
            <a href="https://meta-gen.registermysite.com" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">Meta Title Generator</a>
            <a href="https://email-gen.registermysite.com" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">Email Template Generator</a>
            <a href="https://ai.editor.registermysite.com" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">HTML Website Generator</a>
            <a href="/tools" class="block px-4 py-2.5 text-blue-400 hover:text-blue-300">View all tools →</a>
          </div>

          <a href="/Web_Design" class="px-2 py-3 text-slate-300 hover:text-blue-400">Web Design</a>
          <a href="/SEO_Optimization" class="px-2 py-3 text-slate-300 hover:text-blue-400">SEO</a>
          <a href="/Business_Email" class="px-2 py-3 text-slate-300 hover:text-blue-400">Business Email</a>
          <a href="/docs" class="px-2 py-3 text-slate-300 hover:text-blue-400">Docs</a>
          <a href="/contact" class="px-2 py-3 text-slate-300 hover:text-blue-400">Contact</a>
          <a href="/login" class="mx-2 mt-2 mb-3 cta-primary text-center font-semibold py-3 rounded-xl">Login / Sign up</a>
        </nav>
      </div>
    </div>
  </header>

  <!-- ========== HERO ========== -->
  <section class="hero">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-24 w-full relative z-10">
      <p class="text-blue-400 text-sm font-semibold tracking-wide uppercase mb-4">Web development agency</p>
      <h1 class="section-title text-4xl sm:text-5xl md:text-6xl font-bold leading-tight mb-5 max-w-3xl">
        Your Business <span class="gradient-text">Online</span>
      </h1>
      <p class="text-slate-300 text-lg md:text-xl max-w-2xl leading-relaxed mb-8">
        Multi-platform presence that ties your website, Google Business, Yelp, and social profiles together —
        so customers find a professional brand, not scattered listings.
      </p>

      <form id="hero-domain-form" class="domain-search-wrap mb-4" autocomplete="off">
        <input
          type="text"
          id="hero-domain-input"
          class="domain-search-input"
          placeholder="Search a domain — e.g. example.com"
          spellcheck="false"
          autocapitalize="off"
          inputmode="url"
          aria-label="Domain name to search"
        />
        <button type="submit" id="hero-domain-btn" class="domain-search-btn">
          <i class="fas fa-search mr-1.5"></i> Search
        </button>
      </form>
      <p id="hero-domain-hint" class="text-sm text-slate-500 mb-6 min-h-[1.25rem]"></p>

      <div class="flex flex-col sm:flex-row gap-3 sm:gap-4 mb-10">
        <a href="/contact" class="cta-secondary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl text-base">
          <i class="fas fa-envelope"></i>
          Contact Us Today
        </a>
        <a href="/tools/Domain_Search" class="cta-secondary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl text-base text-sm">
          Advanced domain tools →
        </a>
      </div>

      <!-- Platform status pills -->
      <div class="flex flex-wrap gap-2">
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Yelp · Claimed &amp; Linked</span>
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Google Business · Claimed &amp; Linked</span>
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Facebook · Connected</span>
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Instagram · Connected</span>
      </div>
    </div>
  </section>

  <!-- ========== CORE SERVICES ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-20">
    <div class="text-center mb-12">
      <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
        Everything Your Business Needs <span class="gradient-text">Online</span>
      </h2>
      <p class="text-slate-400 text-base md:text-lg max-w-2xl mx-auto leading-relaxed">
        From domain setup to SEO-powered websites and professional email — we handle the technical side
        so you can focus on customers.
      </p>
    </div>

    <div class="grid sm:grid-cols-2 gap-5">
      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-blue-500/15 text-blue-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-globe"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">Domain &amp; DNS Setup</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          We register or connect your domain, configure DNS records correctly, and make sure everything
          points to your new site with zero downtime.
        </p>
      </article>

      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-violet-500/15 text-violet-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-magnifying-glass"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">SEO Optimization</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Technical SEO, schema markup, local SEO, and strategic linking of all your platform profiles
          so Google ranks your business higher.
        </p>
      </article>

      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-pink-500/15 text-pink-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-palette"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">Web Design &amp; Templates</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Beautiful, conversion-focused designs and ready-to-use industry templates. Fully responsive
          and mobile-first for every device.
        </p>
      </article>

      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-emerald-500/15 text-emerald-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-envelope"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">Custom Business Email</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Professional email addresses (@yourbusiness.com) with auto-reply workers that respond
          instantly while you’re busy with customers.
        </p>
      </article>
    </div>
  </section>

  <!-- ========== HOW IT WORKS ========== -->
  <section class="border-y border-white/5 bg-white/[0.015]">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-20">
      <div class="text-center mb-12">
        <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
          How It <span class="gradient-text">Works</span>
        </h2>
        <p class="text-slate-400 max-w-xl mx-auto">
          From scattered listings to a fully connected online presence in four simple steps.
        </p>
      </div>

      <div class="grid md:grid-cols-2 gap-5">
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">1</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Audit Your Listings</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              We find every unclaimed or disconnected profile for your business across major platforms.
            </p>
          </div>
        </div>
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">2</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Build Your Website</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              Choose a template or go custom. We create a site that showcases your business and services.
            </p>
          </div>
        </div>
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">3</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Claim &amp; Link Everything</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              We claim your Yelp, Google Business, and other accounts and link them back to your new website.
            </p>
          </div>
        </div>
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">4</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Launch &amp; Rank</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              DNS, SEO, emails, and analytics go live. Your business becomes discoverable and professional.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ========== TOOLS ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-20">
    <div class="text-center mb-12">
      <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
        Built for Developers &amp; <span class="gradient-text">Businesses</span>
      </h2>
      <p class="text-slate-400 max-w-xl mx-auto">
        Powerful tools when you need them, simple when you don’t.
      </p>
    </div>

    <div class="grid md:grid-cols-3 gap-5">
      <article class="card rounded-2xl p-6">
        <div class="text-blue-400 text-xl mb-3"><i class="fas fa-file-lines"></i></div>
        <h3 class="font-semibold text-lg mb-2">Templates</h3>
        <p class="text-sm text-slate-400 leading-relaxed mb-4">
          Browse dozens of industry-ready website templates. Restaurants, salons, contractors, clinics —
          pick one and customize in minutes.
        </p>
        <a href="/templates" class="text-sm text-blue-400 hover:text-blue-300 font-medium">Browse templates →</a>
      </article>
      <article class="card rounded-2xl p-6">
        <div class="text-violet-400 text-xl mb-3"><i class="fas fa-bolt"></i></div>
        <h3 class="font-semibold text-lg mb-2">API</h3>
        <p class="text-sm text-slate-400 leading-relaxed mb-4">
          Programmatically manage domains, DNS, listings, and site deployments. Perfect for agencies
          managing multiple client sites.
        </p>
        <a href="/api" class="text-sm text-blue-400 hover:text-blue-300 font-medium">API reference →</a>
      </article>
      <article class="card rounded-2xl p-6">
        <div class="text-pink-400 text-xl mb-3"><i class="fas fa-book"></i></div>
        <h3 class="font-semibold text-lg mb-2">Docs</h3>
        <p class="text-sm text-slate-400 leading-relaxed mb-4">
          Clear documentation for DNS, email workers, SEO best practices, and integrating third-party
          platforms with your site.
        </p>
        <a href="/docs" class="text-sm text-blue-400 hover:text-blue-300 font-medium">Read docs →</a>
      </article>
    </div>
  </section>

  <!-- ========== EXTRA VALUE (LA/OC + ownership) ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 pb-16">
    <div class="grid md:grid-cols-2 gap-5">
      <div class="card rounded-2xl p-6 md:p-8">
        <div class="text-emerald-400 mb-3"><i class="fas fa-map-marker-alt"></i></div>
        <h3 class="section-title text-xl font-bold mb-2">In-person in LA &amp; OC</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Prefer face-to-face? We offer service calls across Los Angeles and Orange County —
          discovery meetings, design reviews, staff training, and on-site help. Remote clients
          are fully supported online.
        </p>
      </div>
      <div class="card rounded-2xl p-6 md:p-8">
        <div class="text-blue-400 mb-3"><i class="fas fa-key"></i></div>
        <h3 class="section-title text-xl font-bold mb-2">You own the code &amp; data</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Built in-house. Source, assets, and deploy config are yours — not locked inside a page builder
          you rent forever. You dream. We code.
        </p>
      </div>
    </div>
  </section>

  <!-- ========== FINAL CTA ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 pb-20">
    <div class="card rounded-3xl p-8 md:p-12 text-center relative overflow-hidden">
      <div class="absolute inset-0 bg-gradient-to-br from-blue-600/10 via-transparent to-violet-600/10 pointer-events-none"></div>
      <div class="relative">
        <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
          Ready to Claim Your Online Presence?
        </h2>
        <p class="text-slate-400 max-w-xl mx-auto mb-8 leading-relaxed">
          Stop losing customers to unclaimed listings. Let’s build the website that ties everything
          together and gets you found.
        </p>
        <div class="flex flex-col sm:flex-row items-center justify-center gap-3 sm:gap-4">
          <a href="/contact" class="cta-primary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl">
            Contact Us Today
          </a>
          <a href="/tools/Domain_Search" class="cta-secondary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl">
            Search a Domain
          </a>
        </div>
      </div>
    </div>
  </section>

<div class="announcement-banner">
  <div class="banner-container">
    <div class="banner-text" id="bannerText"></div>
  </div>
</div>

<style>
.announcement-banner {
  width: 100%;
  height: 45px;
  background: linear-gradient(135deg, #0a0a0f, #0a0a0f);
  color: white;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 24px;
  font-weight: bold;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  position: relative;
  box-shadow: 0 2px 8px rgba(0,0,0,0.2);
  margin: 10px auto;
  border-radius: 4px;
}

.banner-container {
  width: 100%;
  height: 100%;
  position: relative;
}

.banner-text {
  position: absolute;
  width: 100%;
  text-align: center;
  padding: 0 20px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;

  /* Initial state */
  opacity: 0;
  transform: translateX(50px); /* Start slightly to the right */
  transition: all 0.7s cubic-bezier(0.4, 0, 0.2, 1);
}

/* Active state - visible and centered */
.banner-text.active {
  opacity: 1;
  transform: translateX(0);
}

/* Previous slide (for outgoing) */
.banner-text.out {
  opacity: 0;
  transform: translateX(-50px);
}
</style>

<script>
// Messages - edit these freely
const messages = [
  "🤖 Cloudflare AI",
  "GitHub for Version Control",
  "Google Business Claimed & Linked",
  "Facebook Optimization",
  "Rank #1 on Google",
  "Fine Tuned SEO Strategies",
  "Search Engine Optimized",
  "Analytics Engines",
  "Email Tracking Pixels",
  "Click Tracking",
  "Generate Email Templates",
  "Generate Keywords",
  "Generate Meta Tags",
  "Custom Smart AI Bots",
  "Email Automation",
  "Send Custom Emails",
  "Advanced Dashboards",
  "American Made Technology",
  "24/7 Live Developer Support",
  "You own the Source Code",
  "Custom Builds shipped World Wide"
];

let currentIndex = 0;
const bannerText = document.getElementById('bannerText');

function showMessage(index) {
  bannerText.innerHTML = messages[index];
  bannerText.classList.add('active');
}

function nextMessage() {
  const currentText = bannerText;

  // Start outgoing animation
  currentText.classList.add('out');

  setTimeout(() => {
    currentText.classList.remove('active', 'out');

    // Move to next message
    currentIndex = (currentIndex + 1) % messages.length;
    showMessage(currentIndex);
  }, 700); // Match transition duration
}

// Initialize first message
showMessage(0);

// Auto-rotate every 4.2 seconds
setInterval(nextMessage, 4200);
</script>
  <!-- Domain result modal -->
  <div id="domain-modal" class="domain-modal-backdrop" role="dialog" aria-modal="true" aria-labelledby="domain-modal-title" hidden>
    <div class="domain-modal">
      <div class="flex items-start justify-between gap-3 mb-4">
        <div class="flex items-center gap-3">
          <div id="domain-modal-icon" class="w-11 h-11 rounded-xl flex items-center justify-center text-lg bg-emerald-500/15 text-emerald-400">
            <i class="fas fa-check-circle"></i>
          </div>
          <h2 id="domain-modal-title" class="section-title text-xl font-bold">Domain Available!</h2>
        </div>
        <button type="button" id="domain-modal-close" class="text-slate-500 hover:text-white w-9 h-9 rounded-lg hover:bg-white/5" aria-label="Close">
          <i class="fas fa-times"></i>
        </button>
      </div>
      <p id="domain-modal-message" class="text-slate-300 text-sm leading-relaxed mb-6">
        Great news! <strong class="text-white" id="domain-modal-name">example.com</strong> is available for registration.
      </p>
      <div class="flex flex-col sm:flex-row gap-3">
        <a id="domain-modal-register" href="/register" class="cta-primary flex-1 text-center font-semibold py-3 rounded-xl text-sm">
          Register this domain
        </a>
        <button type="button" id="domain-modal-dismiss" class="cta-secondary flex-1 font-semibold py-3 rounded-xl text-sm">
          Search again
        </button>
      </div>
      <p class="text-xs text-slate-500 mt-4 text-center">
        Availability is checked via public DNS and is not a guarantee of registration success.
      </p>
    </div>
  </div>

  <!-- ========== FOOTER ========== -->
  <footer class="border-t border-white/10 py-10">
    <!--=== visitor counter ===-->
      <div id="my-visitor-counter"></div>
<script
  src="https://visitor-counter.registermysite.com/widget.js"
  data-container="my-visitor-counter"
></script>
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="flex flex-col md:flex-row md:items-start justify-between gap-8 mb-8">
        <div>
          <div class="flex items-center gap-2 mb-3">
           <!-- <div class="w-8 h-8 rounded-lg bg-gradient-to-br from-blue-500 to-violet-600 flex items-center justify-center font-bold text-white text-sm">R</div>
            <span class="font-semibold">registermysite.com</span> -->
          </div>
          <p class="text-sm text-slate-500 max-w-xs">Web development for multi-platform business presence. Domains, design, SEO, and email.</br>
          Register your website to start linking your accounts and Rank higher in search results against your competitors. Claim, Link and Rank. </p>
        </div>
        <div class="grid grid-cols-2 sm:grid-cols-3 gap-8 text-sm">
          <div>
            <div class="text-slate-400 font-medium mb-3">Product</div>
            <ul class="space-y-2 text-slate-500">
              <li><a href="/services" class="hover:text-blue-400">Services</a></li>
              <li><a href="/pricing" class="hover:text-blue-400">Pricing</a></li>
              <li><a href="/tools" class="hover:text-blue-400">Tools</a></li>
              <li><a href="/templates" class="hover:text-blue-400">Templates</a></li>
            </ul>
          </div>
          <div>
            <div class="text-slate-400 font-medium mb-3">Company</div>
            <ul class="space-y-2 text-slate-500">
              <li><a href="/docs" class="hover:text-blue-400">Docs</a></li>
              <li><a href="/api" class="hover:text-blue-400">API</a></li>
              <li><a href="/contact" class="hover:text-blue-400">Contact</a></li>
              <li><a href="/login" class="hover:text-blue-400">Login</a></li>
              <li><a href="/sitemap.html" class="hover:text-blue-400">Site Map</a></li>
            </ul>
          </div>
          <div>
            <div class="text-slate-400 font-medium mb-3">Contact</div>
            <ul class="space-y-2 text-slate-500">
              <li><a href="tel:+15627514597" class="hover:text-blue-400">(562) 751-4597</a></li>
              <li><a href="/cdn-cgi/l/email-protection#c9a0a7afa689bbacaea0babdacbba4b0baa0bdace7aaa6a4" class="hover:text-blue-400"><span class="__cf_email__" data-cfemail="a3cacdc5cce3d1c6c4cad0d7c6d1cedad0cad7c68dc0ccce">[email&#160;protected]</span></a></li>
            </ul>
          <img src="https://uploads.registermysite.com/applist.webp" alt="Venmo, CashApp, Zelle, Paypal payment methods accepted" id="PaymentLogo" style="max-width: 100%; height: auto;">
          </div>
        </div>
      </div>
       <a href="https://x.com/diyregistry" class="logo-circle" title="X.com">
  <img src="https://uploads.registermysite.com/favicon-x.png" alt="X" />
</a>
<a href="https://youtube.com/@RegisterMySite" href="https://www.youtube.com/channel/UCwwGNwZJ5JizhMoFU_Z-WOw" class="logo-circle" title="YouTube">
  <img src="https://uploads.registermysite.com/favicon-youtube.png" alt="YT" />
</a>
<a href="https://yelp.com/RegisterMySite" class="logo-circle" title="yelp">
  <img src="https://uploads.registermysite.com/yelp-icon.png" alt="yelp" />
</a>
<a href="https://www.tiktok.com/@registermysite?_r=1&_t=ZP-98fvlLBUhji" class="logo-circle" title="TikTok">
  <img src="https://uploads.registermysite.com/favicon-tiktok.png" alt="TikTok" />
</a>
<a href="https://instagram.com/RegisterMySite" class="logo-circle" title="InstaGram">
  <img src="https://uploads.registermysite.com/favicon-instagram.png" alt="Instagram" />
</a>
<a href="https://github.com/RegisterMySite-com" class="logo-circle" title="GitHub">
  <img src="https://uploads.registermysite.com/github-icon.jpeg" alt="GitHub" />
</a>
<a href="https://google.registermysite.com/Google-Business-Profile" class="logo-circle" title="Google">
  <img src="https://uploads.registermysite.com/google-icon.jpeg" alt="Google" />
</a>
<a href="https://www.facebook.com/profile.php?id=61592420500053&mibextid=ZbWKwL" class="logo-circle" title="Facebook">
  <img src="https://uploads.registermysite.com/facebook-icon.png" alt="Facebook" />
</a>
                <!-- Logo -->
        <a href="/" class="flex items-center gap-3 shrink-0">
          <div class="flex items-center gap-3">
        <img src="https://uploads.registermysite.com/registermysite.jpg" alt="Logo" class="h-10 w-10 rounded-xl object-cover bg-white/20">

          <div class="leading-tight">
            <span class="text-lg font-bold tracking-tight">RegisterMySite</span><span class="text-blue-400">.com</span>
          </div>
        </a>
            </div>
    </div>
  </footer>
<script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script>
  window.RMS_CHAT = {
    url: "https://ai.registermysite.com",
    title: "RegisterMySite AI",
    position: "right",   // or "left"
    openOnLoad: true,
    buttonLabel: "Chat"
  };
</script>
<script src="https://registermysite.com/ai-chat-widget.js" defer></script>
  <script>
    /* —— Mobile nav —— */
    const menuBtn = document.getElementById('menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');
    const menuIcon = document.getElementById('menu-icon');
    const toolsToggle = document.getElementById('tools-toggle');
    const toolsSub = document.getElementById('tools-sub');
    const toolsChevron = document.getElementById('tools-chevron');

    menuBtn.addEventListener('click', () => {
      const open = mobileMenu.classList.toggle('open');
      menuBtn.setAttribute('aria-expanded', open ? 'true' : 'false');
      menuIcon.className = open ? 'fas fa-times text-lg' : 'fas fa-bars text-lg';
      if (!open) {
        toolsSub.classList.remove('open');
        toolsChevron.style.transform = '';
      }
    });

    toolsToggle.addEventListener('click', () => {
      const open = toolsSub.classList.toggle('open');
      toolsChevron.style.transform = open ? 'rotate(180deg)' : '';
    });

    /* —— Domain search (Google DNS-over-HTTPS, same idea as Domain_Search) —— */
    const form = document.getElementById('hero-domain-form');
    const input = document.getElementById('hero-domain-input');
    const btn = document.getElementById('hero-domain-btn');
    const hint = document.getElementById('hero-domain-hint');
    const modal = document.getElementById('domain-modal');
    const modalTitle = document.getElementById('domain-modal-title');
    const modalMessage = document.getElementById('domain-modal-message');
    const modalName = document.getElementById('domain-modal-name');
    const modalIcon = document.getElementById('domain-modal-icon');
    const modalRegister = document.getElementById('domain-modal-register');
    const modalClose = document.getElementById('domain-modal-close');
    const modalDismiss = document.getElementById('domain-modal-dismiss');

    function normalizeDomain(raw) {
      let d = (raw || '').trim().toLowerCase();
      d = d.replace(/^https?:\/\//, '').replace(/^www\./, '').split('/')[0].split('?')[0];
      return d;
    }

    function isValidDomain(d) {
      return /^[a-z0-9]([a-z0-9-]{0,61}[a-z0-9])?(\.[a-z0-9]([a-z0-9-]{0,61}[a-z0-9])?)+$/i.test(d);
    }

    /** NXDOMAIN / no answers ≈ available; answers present ≈ taken */
    async function checkViaGoogleDNS(domain) {
      const url = `https://dns.google/resolve?name=${encodeURIComponent(domain)}&type=A`;
      const res = await fetch(url, { headers: { Accept: 'application/dns-json' } });
      if (!res.ok) throw new Error('DNS lookup failed');
      const data = await res.json();
      // Status 3 = NXDOMAIN (available). Status 0 with Answer = registered.
      if (data.Status === 3) return { available: true };
      if (data.Status === 0 && data.Answer && data.Answer.length > 0) return { available: false };
      // No answer records often means not resolving (treat as likely available)
      if (data.Status === 0 && (!data.Answer || data.Answer.length === 0)) return { available: true };
      return { available: false };
    }

    function openModal({ available, domain }) {
      modal.hidden = false;
      requestAnimationFrame(() => modal.classList.add('open'));

      if (available) {
        modalTitle.textContent = 'Domain Available!';
        modalIcon.className = 'w-11 h-11 rounded-xl flex items-center justify-center text-lg bg-emerald-500/15 text-emerald-400';
        modalIcon.innerHTML = '<i class="fas fa-check-circle"></i>';
        modalMessage.innerHTML = `Great news! <strong class="text-white" id="domain-modal-name">${escapeHtml(domain)}</strong> is available for registration.`;
        modalRegister.href = `https://registermysite.com/register?domain=${encodeURIComponent(domain)}`;
        modalRegister.style.display = '';
        modalRegister.textContent = 'Register this domain';
      } else {
        modalTitle.textContent = 'Domain Taken';
        modalIcon.className = 'w-11 h-11 rounded-xl flex items-center justify-center text-lg bg-amber-500/15 text-amber-400';
        modalIcon.innerHTML = '<i class="fas fa-times-circle"></i>';
        modalMessage.innerHTML = `<strong class="text-white">${escapeHtml(domain)}</strong> appears to be registered. Try another name or check advanced tools for alternatives.`;
        modalRegister.href = `/tools/Domain_Search`;
        modalRegister.textContent = 'Try advanced search';
      }
    }

    function closeModal() {
      modal.classList.remove('open');
      setTimeout(() => { modal.hidden = true; }, 200);
    }

    function escapeHtml(s) {
      return String(s)
        .replace(/&/g, '&amp;')
        .replace(/</g, '&lt;')
        .replace(/>/g, '&gt;')
        .replace(/"/g, '&quot;');
    }

    form.addEventListener('submit', async (e) => {
      e.preventDefault();
      const domain = normalizeDomain(input.value);
      hint.textContent = '';

      if (!domain) {
        hint.textContent = 'Enter a domain name to search.';
        hint.className = 'text-sm text-amber-400 mb-6 min-h-[1.25rem]';
        return;
      }
      if (!isValidDomain(domain)) {
        hint.textContent = 'Enter a valid domain like example.com';
        hint.className = 'text-sm text-amber-400 mb-6 min-h-[1.25rem]';
        return;
      }

      btn.disabled = true;
      btn.innerHTML = '<i class="fas fa-spinner fa-spin mr-1.5"></i> Checking…';
      hint.textContent = `Checking ${domain}…`;
      hint.className = 'text-sm text-slate-400 mb-6 min-h-[1.25rem]';

      try {
        const result = await checkViaGoogleDNS(domain);
        hint.textContent = '';
        openModal({ available: result.available, domain });
      } catch (err) {
        console.error(err);
        hint.textContent = 'Lookup failed. Please try again or use Domain Search tools.';
        hint.className = 'text-sm text-red-400 mb-6 min-h-[1.25rem]';
      } finally {
        btn.disabled = false;
        btn.innerHTML = '<i class="fas fa-search mr-1.5"></i> Search';
      }
    });

    modalClose.addEventListener('click', closeModal);
    modalDismiss.addEventListener('click', () => {
      closeModal();
      input.focus();
    });
    modal.addEventListener('click', (e) => {
      if (e.target === modal) closeModal();
    });
    document.addEventListener('keydown', (e) => {
      if (e.key === 'Escape' && modal.classList.contains('open')) closeModal();
    });
  </script>
</body>
</html></doc><doc title="Templates &amp; Tools" desc="Industry-ready website templates"><!DOCTYPE html>
<html lang="en">
<head>
   <!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-GMLQJKKPPP"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-GMLQJKKPPP');
</script>
   <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Templates & Tools — registermysite.com</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Space+Grotesk:wght@500;600;700&display=swap');
        body { font-family: 'Inter', system-ui, sans-serif; background: #0a0a0f; color: #e2e8f0; }
        .gradient-text { background: linear-gradient(135deg, #60a5fa, #a78bfa, #f472b6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .card { background: rgba(255,255,255,0.03); border: 1px solid rgba(255,255,255,0.08); transition: all 0.3s ease; }
        .card:hover { border-color: rgba(96,165,250,0.4); transform: translateY(-4px); box-shadow: 0 20px 40px rgba(0,0,0,0.4); }
        .section-title { font-family: 'Space Grotesk', sans-serif; }
        .popular { border: 2px solid #60a5fa; position: relative; }
        .popular::before {
            content: "MOST POPULAR";
            position: absolute;
            top: -12px;
            left: 50%;
            transform: translateX(-50%);
            background: linear-gradient(90deg, #3b82f6, #8b5cf6);
            color: white;
            font-size: 11px;
            font-weight: 700;
            padding: 4px 14px;
            border-radius: 999px;
            letter-spacing: 0.5px;
        }
    </style>
</head>
<body class="min-h-screen">

    <!-- Header -->
    <header class="border-b border-white/10 sticky top-0 z-50 backdrop-blur-xl bg-black/60">
        <div class="max-w-7xl mx-auto px-6 py-5 flex items-center justify-between">
            <div class="flex items-center gap-3">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-br from-blue-500 to-violet-600 flex items-center justify-center font-bold text-white text-lg">R</div>
                <div>
                    <span class="text-xl font-bold tracking-tight">registermysite</span><span class="text-blue-400">.com</span>
                </div>
            </div>
            <nav class="hidden md:flex items-center gap-8 text-sm font-medium">
                <a href="/templates.html" class="hover:text-blue-400 transition">Templates</a>
                <a href="/tools.html" class="hover:text-blue-400 transition">QR Tools</a>
                <a href="/dashboard.html" class="hover:text-blue-400 transition">Dashboard</a>
                <a href="/addons.html" class="hover:text-blue-400 transition">Add-ons</a>
                <a href="/pricing.html" class="hover:text-blue-400 transition">Pricing</a>
                </nav>
            <a href="#contact" class="bg-blue-600 hover:bg-blue-500 transition px-6 py-2.5 rounded-full text-sm font-semibold">Get Started</a>
        </div>

        </header>

    <!-- Hero -->
    <section class="relative overflow-hidden">
        <div class="absolute inset-0 bg-gradient-to-b from-blue-900/20 via-transparent to-transparent"></div>
        <div class="max-w-7xl mx-auto px-6 pt-24 pb-20 text-center relative">
            <p class="text-blue-400 font-semibold tracking-widest uppercase text-sm mb-4">Website Templates • Tools • Analytics</p>
            <h1 class="section-title text-5xl md:text-7xl font-bold leading-tight mb-6">
                You Dream.<br>
                <span class="gradient-text">We Code.</span>
            </h1>
            <p class="text-xl text-slate-400 max-w-2xl mx-auto mb-10">
                Professional website templates, powerful QR generators, and a private analytics dashboard — all under one roof at registermysite.com.
            </p>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="#templates" class="bg-blue-600 hover:bg-blue-500 px-8 py-4 rounded-2xl font-semibold transition">Browse Templates</a>
                <a href="#pricing" class="border border-white/20 hover:border-blue-400 px-8 py-4 rounded-2xl font-semibold transition">View Pricing</a>
            </div>
        </div>
    </section>

    <!-- Templates Section -->
    <section id="templates" class="max-w-7xl mx-auto px-6 py-24">
        <div class="text-center mb-16">
            <h2 class="section-title text-4xl font-bold mb-4">Website Templates</h2>
            <p class="text-slate-400 max-w-2xl mx-auto">Ready-to-launch designs for every business type. Fully customizable, mobile-first, and SEO-optimized.</p>
        </div>

        <div class="grid md:grid-cols-2 gap-8">
            <!-- eCommerce -->
            <div class="card rounded-3xl p-10">
                <div class="flex items-center gap-3 mb-6">
                    <div class="w-12 h-12 rounded-2xl bg-blue-500/20 flex items-center justify-center text-blue-400 text-xl">
                        <i class="fas fa-shopping-cart"></i>
                    </div>
                    <div>
                        <h3 class="text-2xl font-bold">eCommerce Templates</h3>
                        <p class="text-sm text-slate-400">Sell products online with confidence</p>
                    </div>
                </div>
                <p class="text-slate-300 mb-6 leading-relaxed">
                    High-converting storefronts built for modern online retail. Product grids, cart & checkout flows, inventory management, and payment integrations.
                </p>
                <div class="bg-black/40 rounded-2xl p-6 border border-white/5 mb-6">
                    <p class="text-xs uppercase tracking-widest text-blue-400 mb-2">Live Example</p>
                    <a href="https://shastastash.com" target="_blank" class="text-lg font-semibold hover:text-blue-400 transition flex items-center gap-2">
                        shastastash.com <i class="fas fa-external-link-alt text-sm"></i>
                    </a>
                    <p class="text-sm text-slate-400 mt-2">A fully functional eCommerce experience powered by our template system.</p>
                </div>
                <ul class="space-y-3 text-sm text-slate-300">
                    <li class="flex items-center gap-2"><i class="fas fa-check text-blue-400"></i> Product catalogs & variants</li>
                    <li class="flex items-center gap-2"><i class="fas fa-check text-blue-400"></i> Stripe / PayPal / Crypto payments</li>
                    <li class="flex items-center gap-2"><i class="fas fa-check text-blue-400"></i> Inventory tracking & order management</li>
                    <li class="flex items-center gap-2"><i class="fas fa-check text-blue-400"></i> Mobile-optimized checkout</li>
                </ul>
            </div>

            <!-- Service Based -->
            <div class="card rounded-3xl p-10">
                <div class="flex items-center gap-3 mb-6">
                    <div class="w-12 h-12 rounded-2xl bg-violet-500/20 flex items-center justify-center text-violet-400 text-xl">
                        <i class="fas fa-tools"></i>
                    </div>
                    <div>
                        <h3 class="text-2xl font-bold">Service-Based Templates</h3>
                        <p class="text-sm text-slate-400">Book clients & showcase your work</p>
                    </div>
                </div>
                <p class="text-slate-300 mb-6 leading-relaxed">
                    Perfect for local businesses, contractors, detailers, salons, and professional services. Booking systems, galleries, testimonials, and contact funnels.
                </p>
                <div class="bg-black/40 rounded-2xl p-6 border border-white/5 mb-6">
                    <p class="text-xs uppercase tracking-widest text-violet-400 mb-2">Live Example</p>
                    <a href="https://automarinedetailers.com" target="_blank" class="text-lg font-semibold hover:text-violet-400 transition flex items-center gap-2">
                        automarinedetailers.com <i class="fas fa-external-link-alt text-sm"></i>
                    </a>
                    <p class="text-sm text-slate-400 mt-2">A polished service business site with booking-ready design.</p>
                </div>
                <ul class="space-y-3 text-sm text-slate-300">
                    <li class="flex items-center gap-2"><i class="fas fa-check text-violet-400"></i> Online booking & calendars</li>
                    <li class="flex items-center gap-2"><i class="fas fa-check text-violet-400"></i> Before/After galleries</li>
                    <li class="flex items-center gap-2"><i class="fas fa-check text-violet-400"></i> Service packages & pricing</li>
                    <li class="flex items-center gap-2"><i class="fas fa-check text-violet-400"></i> Lead capture forms</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- QR Tools Section -->
    <section id="tools" class="bg-gradient-to-b from-transparent via-blue-950/20 to-transparent py-24">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="section-title text-4xl font-bold mb-4">QR Code & Barcode Tools</h2>
                <p class="text-slate-400 max-w-2xl mx-auto">Generate professional QR codes and barcodes instantly — no account required for basic use.</p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
                <div class="card rounded-2xl p-8 text-center">
                    <div class="w-14 h-14 mx-auto rounded-2xl bg-green-500/20 flex items-center justify-center text-green-400 text-2xl mb-5">
                        <i class="fas fa-dollar-sign"></i>
                    </div>
                    <h3 class="font-bold text-lg mb-2">Cash App Pay QR</h3>
                    <p class="text-sm text-slate-400">Create branded Cash App payment QR codes for instant mobile payments.</p>
                </div>

                <div class="card rounded-2xl p-8 text-center">
                    <div class="w-14 h-14 mx-auto rounded-2xl bg-amber-500/20 flex items-center justify-center text-amber-400 text-2xl mb-5">
                        <i class="fab fa-bitcoin"></i>
                    </div>
                    <h3 class="font-bold text-lg mb-2">Bitcoin Pay QR</h3>
                    <p class="text-sm text-slate-400">BIP21-compliant Bitcoin payment QR codes with amount & message support.</p>
                </div>

                <div class="card rounded-2xl p-8 text-center">
                    <div class="w-14 h-14 mx-auto rounded-2xl bg-blue-500/20 flex items-center justify-center text-blue-400 text-2xl mb-5">
                        <i class="fas fa-qrcode"></i>
                    </div>
                    <h3 class="font-bold text-lg mb-2">Base64 QR + Scanner</h3>
                    <p class="text-sm text-slate-400">Encode any text into Base64 QR codes with built-in scanner & decoder.</p>
                </div>

                <div class="card rounded-2xl p-8 text-center">
                    <div class="w-14 h-14 mx-auto rounded-2xl bg-pink-500/20 flex items-center justify-center text-pink-400 text-2xl mb-5">
                        <i class="fas fa-barcode"></i>
                    </div>
                    <h3 class="font-bold text-lg mb-2">PDF417 Barcodes</h3>
                    <p class="text-sm text-slate-400">High-capacity PDF417 barcodes ideal for inventory tracking & shipping labels.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Dashboard Section -->
    <section id="dashboard" class="max-w-7xl mx-auto px-6 py-24">
        <div class="grid lg:grid-cols-2 gap-16 items-center">
            <div>
                <p class="text-blue-400 font-semibold tracking-widest uppercase text-sm mb-3">Private Customer Dashboard</p>
                <h2 class="section-title text-4xl font-bold mb-6">Link Shortener + Rich Analytics</h2>
                <p class="text-slate-300 text-lg leading-relaxed mb-8">
                    Every customer receives a secure personal login to their private dashboard. Create short links that generate QR codes packed with rich analytics captured on every scan.
                </p>
                <ul class="space-y-4 mb-10">
                    <li class="flex items-start gap-3">
                        <i class="fas fa-chart-line text-blue-400 mt-1"></i>
                        <div>
                            <strong>Total Scans</strong>
                            <p class="text-sm text-slate-400">Real-time count of every QR scan worldwide.</p>
                        </div>
                    </li>
                    <li class="flex items-start gap-3">
                        <i class="fas fa-clock text-blue-400 mt-1"></i>
                        <div>
                            <strong>Timestamp</strong>
                            <p class="text-sm text-slate-400">Exact date & time of each scan.</p>
                        </div>
                    </li>
                    <li class="flex items-start gap-3">
                        <i class="fas fa-globe text-blue-400 mt-1"></i>
                        <div>
                            <strong>IP Address</strong>
                            <p class="text-sm text-slate-400">Geographic & network origin of the visitor.</p>
                        </div>
                    </li>
                    <li class="flex items-start gap-3">
                        <i class="fas fa-mobile-alt text-blue-400 mt-1"></i>
                        <div>
                            <strong>User Agent</strong>
                            <p class="text-sm text-slate-400">Device, browser, and OS information.</p>
                        </div>
                    </li>
                    <li class="flex items-start gap-3">
                        <i class="fas fa-link text-blue-400 mt-1"></i>
                        <div>
                            <strong>Referrer</strong>
                            <p class="text-sm text-slate-400">Where the visitor came from before scanning.</p>
                        </div>
                    </li>
                </ul>
                <a href="#contact" class="inline-flex items-center gap-2 bg-blue-600 hover:bg-blue-500 px-8 py-4 rounded-2xl font-semibold transition">
                    Request Dashboard Access <i class="fas fa-arrow-right"></i>
                </a>
            </div>
            <div class="card rounded-3xl p-8">
                <div class="bg-black/50 rounded-2xl p-6 border border-white/10">
                    <div class="flex items-center justify-between mb-6">
                        <span class="text-sm font-mono text-slate-400">dashboard.registermysite.com</span>
                        <span class="text-xs bg-green-500/20 text-green-400 px-3 py-1 rounded-full">LIVE</span>
                    </div>
                    <div class="space-y-4 font-mono text-sm">
                        <div class="flex justify-between border-b border-white/5 pb-3">
                            <span class="text-slate-400">Total Scans</span>
                            <span class="text-blue-400 font-bold">12,847</span>
                        </div>
                        <div class="flex justify-between border-b border-white/5 pb-3">
                            <span class="text-slate-400">Last Scan</span>
                            <span>2026-07-24 21:47:12</span>
                        </div>
                        <div class="flex justify-between border-b border-white/5 pb-3">
                            <span class="text-slate-400">IP</span>
                            <span>104.28.***.***</span>
                        </div>
                        <div class="flex justify-between border-b border-white/5 pb-3">
                            <span class="text-slate-400">User Agent</span>
                            <span class="truncate max-w-[180px]">iPhone / Safari</span>
                        </div>
                        <div class="flex justify-between">
                            <span class="text-slate-400">Referrer</span>
                            <span class="text-violet-400">instagram.com</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Add-ons -->
    <section id="addons" class="max-w-7xl mx-auto px-6 py-24">
        <div class="text-center mb-16">
            <h2 class="section-title text-4xl font-bold mb-4">Powerful Add-ons</h2>
            <p class="text-slate-400 max-w-2xl mx-auto">Extend any template with ready-made modules. If you can dream it, we can achieve it.</p>
        </div>

        <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
            <div class="card rounded-2xl p-8">
                <i class="fas fa-users text-3xl text-blue-400 mb-4"></i>
                <h3 class="font-bold text-xl mb-2">Visitor Counters</h3>
                <p class="text-sm text-slate-400">Live or historical visitor counters with location heatmaps and peak-hour insights.</p>
            </div>
            <div class="card rounded-2xl p-8">
                <i class="fas fa-comments text-3xl text-violet-400 mb-4"></i>
                <h3 class="font-bold text-xl mb-2">AI Chatbots</h3>
                <p class="text-sm text-slate-400">Smart chat widgets that answer FAQs, capture leads, and book appointments 24/7.</p>
            </div>
            <div class="card rounded-2xl p-8">
                <i class="fas fa-share-alt text-3xl text-pink-400 mb-4"></i>
                <h3 class="font-bold text-xl mb-2">Social Media Carousels</h3>
                <p class="text-sm text-slate-400">Auto-updating Instagram, TikTok, and Facebook feeds that keep your site fresh.</p>
            </div>
            <div class="card rounded-2xl p-8">
                <i class="fas fa-star text-3xl text-amber-400 mb-4"></i>
                <h3 class="font-bold text-xl mb-2">Review Carousels</h3>
                <p class="text-sm text-slate-400">Pull Google, Yelp, and Facebook reviews into beautiful rotating testimonials.</p>
            </div>
            <div class="card rounded-2xl p-8">
                <i class="fas fa-calendar-check text-3xl text-emerald-400 mb-4"></i>
                <h3 class="font-bold text-xl mb-2">Booking Systems</h3>
                <p class="text-sm text-slate-400">Full calendar integration with SMS/email reminders and deposit collection.</p>
            </div>
            <div class="card rounded-2xl p-8">
                <i class="fas fa-magic text-3xl text-cyan-400 mb-4"></i>
                <h3 class="font-bold text-xl mb-2">Custom Everything</h3>
                <p class="text-sm text-slate-400">You dream it — we code it. Custom features, integrations, and workflows on demand.</p>
            </div>
        </div>
    </section>

    <!-- Pricing Tiers -->
    <section id="pricing" class="bg-gradient-to-b from-transparent via-violet-950/20 to-transparent py-24">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="section-title text-4xl font-bold mb-4">Add-on Pricing Tiers</h2>
                <p class="text-slate-400 max-w-2xl mx-auto">Simple, transparent pricing. Choose the package that fits your business needs. All plans include setup & support.</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">

                <!-- Starter -->
                <div class="card rounded-3xl p-10 flex flex-col">
                    <div class="mb-6">
                        <p class="text-sm uppercase tracking-widest text-slate-400 mb-2">Starter</p>
                        <h3 class="text-3xl font-bold mb-1">$49<span class="text-lg text-slate-400 font-normal">/mo</span></h3>
                        <p class="text-sm text-slate-400">Perfect for getting started</p>
                    </div>
                    <ul class="space-y-4 text-sm flex-1 mb-8">
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> Visitor Counter</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> Social Media Carousel (1 feed)</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> Basic Link Shortener</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> QR Code Generator Access</li>
                        <li class="flex items-center gap-3 text-slate-500"><i class="fas fa-times"></i> AI Chatbot</li>
                        <li class="flex items-center gap-3 text-slate-500"><i class="fas fa-times"></i> Review Carousel</li>
                        <li class="flex items-center gap-3 text-slate-500"><i class="fas fa-times"></i> Booking System</li>
                        <li class="flex items-center gap-3 text-slate-500"><i class="fas fa-times"></i> Rich Analytics Dashboard</li>
                    </ul>
                    <a href="#contact" class="block text-center border border-white/20 hover:border-blue-400 py-4 rounded-2xl font-semibold transition">Choose Starter</a>
                </div>

                <!-- Growth (Popular) -->
                <div class="card popular rounded-3xl p-10 flex flex-col bg-blue-950/30">
                    <div class="mb-6">
                        <p class="text-sm uppercase tracking-widest text-blue-400 mb-2">Growth</p>
                        <h3 class="text-3xl font-bold mb-1">$129<span class="text-lg text-slate-400 font-normal">/mo</span></h3>
                        <p class="text-sm text-slate-400">Most popular for growing businesses</p>
                    </div>
                    <ul class="space-y-4 text-sm flex-1 mb-8">
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> Everything in Starter</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> AI Chatbot (up to 500 chats/mo)</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> Review Carousel (Google + Yelp)</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> Social Media Carousels (3 feeds)</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> Rich Analytics Dashboard</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> Link Shortener + QR Analytics</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> Priority Email Support</li>
                        <li class="flex items-center gap-3 text-slate-500"><i class="fas fa-times"></i> Full Booking System</li>
                    </ul>
                    <a href="#contact" class="block text-center bg-blue-600 hover:bg-blue-500 py-4 rounded-2xl font-semibold transition">Choose Growth</a>
                </div>

                <!-- Pro -->
                <div class="card rounded-3xl p-10 flex flex-col">
                    <div class="mb-6">
                        <p class="text-sm uppercase tracking-widest text-violet-400 mb-2">Pro</p>
                        <h3 class="text-3xl font-bold mb-1">$299<span class="text-lg text-slate-400 font-normal">/mo</span></h3>
                        <p class="text-sm text-slate-400">Full power + custom development</p>
                    </div>
                    <ul class="space-y-4 text-sm flex-1 mb-8">
                        <li class="flex items-center gap-3"><i class="fas fa-check text-violet-400"></i> Everything in Growth</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-violet-400"></i> Unlimited AI Chatbot</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-violet-400"></i> Full Booking System + SMS</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-violet-400"></i> Unlimited Social Feeds</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-violet-400"></i> Advanced Analytics + Export</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-violet-400"></i> Custom Feature Development</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-violet-400"></i> Dedicated Support Channel</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-violet-400"></i> White-label Options</li>
                    </ul>
                    <a href="#contact" class="block text-center border border-violet-500/50 hover:bg-violet-600/20 py-4 rounded-2xl font-semibold transition">Choose Pro</a>
                </div>
            </div>

            <p class="text-center text-sm text-slate-500 mt-12">
                All plans billed monthly. Annual billing available with 2 months free. Custom enterprise packages available upon request.
            </p>
        </div>
    </section>

    <!-- CTA -->
    <section id="contact" class="max-w-4xl mx-auto px-6 py-24 text-center">
        <div class="card rounded-3xl p-12 md:p-16">
            <h2 class="section-title text-4xl md:text-5xl font-bold mb-6">
                You Dream.<br>
                <span class="gradient-text">We Code.</span>
            </h2>
            <p class="text-slate-400 text-lg mb-10 max-w-xl mx-auto">
                Ready to launch your site, generate smart QR codes, or unlock your private analytics dashboard? Let’s build something great together.
            </p>
            <a href="/cdn-cgi/l/email-protection#c2aaa7aeaead82b0a7a5abb1b6a7b0afbbb1abb6a7eca1adaf" class="inline-flex items-center gap-3 bg-gradient-to-r from-blue-600 to-violet-600 hover:from-blue-500 hover:to-violet-500 px-10 py-5 rounded-2xl font-bold text-lg transition">
                <i class="fas fa-paper-plane"></i>
                Start Your Project
            </a>
        </div>
    </section>

    <!-- Footer -->
    <footer class="border-t border-white/10 py-12">
        <div class="max-w-7xl mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-6 text-sm text-slate-500">
            <div class="flex items-center gap-2">
                <div class="w-8 h-8 rounded-lg bg-gradient-to-br from-blue-500 to-violet-600 flex items-center justify-center font-bold text-white text-sm">R</div>
                <span>registermysite.com</span>
            </div>
            <p>© 2026 registermysite.com — Templates, Tools & Analytics</p>
            <p class="italic">If you can dream it, we can achieve it.</p>
        </div>
    </footer>

<script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script></body>
</html></doc><doc title="Documentation" desc="Step-by-step guide to domain search, registration, and setup"><!DOCTYPE html>
<html lang="en">
<head>
    <!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-GMLQJKKPPP"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-GMLQJKKPPP');
</script>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>How to Register a Domain & Build Your Website — registermysite.com</title>
    <meta name="description" content="Step-by-step documentation: check domain availability, register your domain, create an account, and collaborate with the RegisterMySite team to build your website.">
    <meta name="robots" content="index, follow">
    <link rel="canonical" href="https://registermysite.com/docs.html">

    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Space+Grotesk:wght@500;600;700&display=swap');

        body {
            font-family: 'Inter', system-ui, sans-serif;
            background: #0a0a0f;
            color: #e2e8f0;
        }

        .section-title {
            font-family: 'Space Grotesk', sans-serif;
        }

        .gradient-text {
            background: linear-gradient(135deg, #60a5fa, #a78bfa, #f472b6);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .card {
            background: rgba(255,255,255,0.03);
            border: 1px solid rgba(255,255,255,0.08);
        }

        .step-number {
            background: linear-gradient(135deg, #3b82f6, #8b5cf6);
            font-family: 'Space Grotesk', sans-serif;
        }

        .step-card:hover {
            border-color: rgba(96, 165, 250, 0.35);
            background: rgba(255,255,255,0.045);
        }

        a.cta-btn {
            background: linear-gradient(135deg, #3b82f6, #8b5cf6);
        }

        a.cta-btn:hover {
            background: linear-gradient(135deg, #60a5fa, #a78bfa);
        }
    </style>
</head>
<body class="min-h-screen">

    <!-- Header -->
    <header class="border-b border-white/10 sticky top-0 z-50 backdrop-blur-xl bg-black/60">
        <div class="max-w-4xl mx-auto px-6 py-5 flex items-center justify-between">
            <a href="https://registermysite.com" class="flex items-center gap-3">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-br from-blue-500 to-violet-600 flex items-center justify-center font-bold text-white text-lg">R</div>
                <div>
                    <span class="text-xl font-bold tracking-tight">registermysite</span><span class="text-blue-400">.com</span>
                </div>
            </a>
            <nav class="hidden sm:flex items-center gap-6 text-sm font-medium">
                <a href="/tools.html" class="hover:text-blue-400 transition">All Tools</a>
                <a href="/tools/Domain_Search" class="hover:text-blue-400 transition">Domain Search</a>
                <a href="/templates.html" class="hover:text-blue-400 transition">Templates</a>
                <a href="/login" class="hover:text-blue-400 transition">Login</a>
            </nav>
        </div>
    </header>

    <!-- Hero -->
    <section class="max-w-4xl mx-auto px-6 pt-16 pb-12 text-center">
        <p class="text-blue-400 font-semibold tracking-widest uppercase text-sm mb-3">Documentation</p>
        <h1 class="section-title text-4xl md:text-5xl font-bold mb-5">
            How to Register a Domain<br>
            <span class="gradient-text">& Build Your Website</span>
        </h1>
        <p class="text-slate-400 text-lg max-w-2xl mx-auto leading-relaxed">
            Follow these clear steps to check domain availability, register your domain,
            create your account, and collaborate with the RegisterMySite team to launch your site.
        </p>
    </section>

    <!-- Quick Overview -->
    <section class="max-w-3xl mx-auto px-6 pb-14">
        <div class="card rounded-3xl p-8 md:p-10">
            <h2 class="section-title text-2xl font-bold mb-6 text-center">Quick Overview</h2>
            <div class="grid sm:grid-cols-2 gap-4 text-sm">
                <div class="flex items-start gap-3 p-4 rounded-2xl bg-black/30 border border-white/5">
                    <i class="fas fa-search text-blue-400 mt-1"></i>
                    <div>
                        <p class="font-semibold text-white">1–2. Search & Check</p>
                        <p class="text-slate-400 mt-1">Find an available domain name</p>
                    </div>
                </div>
                <div class="flex items-start gap-3 p-4 rounded-2xl bg-black/30 border border-white/5">
                    <i class="fas fa-file-signature text-violet-400 mt-1"></i>
                    <div>
                        <p class="font-semibold text-white">3–4. Register</p>
                        <p class="text-slate-400 mt-1">Submit registration details</p>
                    </div>
                </div>
                <div class="flex items-start gap-3 p-4 rounded-2xl bg-black/30 border border-white/5">
                    <i class="fas fa-user-plus text-pink-400 mt-1"></i>
                    <div>
                        <p class="font-semibold text-white">5. Create Account</p>
                        <p class="text-slate-400 mt-1">Log in to start collaborating</p>
                    </div>
                </div>
                <div class="flex items-start gap-3 p-4 rounded-2xl bg-black/30 border border-white/5">
                    <i class="fas fa-code text-emerald-400 mt-1"></i>
                    <div>
                        <p class="font-semibold text-white">6–7. Build & Launch</p>
                        <p class="text-slate-400 mt-1">Work with our team on your site</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Detailed Steps -->
    <section class="max-w-3xl mx-auto px-6 pb-16 space-y-6">

        <!-- Step 1 -->
        <article class="card step-card rounded-3xl p-7 md:p-9 transition duration-200">
            <div class="flex items-start gap-5">
                <div class="step-number w-12 h-12 rounded-2xl flex items-center justify-center text-white font-bold text-lg flex-shrink-0">1</div>
                <div class="flex-1">
                    <h3 class="section-title text-xl font-bold mb-3">Go to Domain Search</h3>
                    <p class="text-slate-400 leading-relaxed mb-5">
                        Open the official domain search tool on RegisterMySite. This is where you will check availability and begin registration.
                    </p>
                    <a href="https://registermysite.com/tools/Domain_Search"
                       class="cta-btn inline-flex items-center gap-2 text-white font-semibold px-5 py-3 rounded-xl transition text-sm">
                        <i class="fas fa-external-link-alt"></i>
                        Open Domain Search Tool
                    </a>
                    <p class="text-xs text-slate-500 mt-4">
                        Direct link: <code class="text-blue-300">registermysite.com/tools/Domain_Search</code>
                    </p>
                </div>
            </div>
        </article>

        <!-- Step 2 -->
        <article class="card step-card rounded-3xl p-7 md:p-9 transition duration-200">
            <div class="flex items-start gap-5">
                <div class="step-number w-12 h-12 rounded-2xl flex items-center justify-center text-white font-bold text-lg flex-shrink-0">2</div>
                <div class="flex-1">
                    <h3 class="section-title text-xl font-bold mb-3">Check Domain Availability</h3>
                    <p class="text-slate-400 leading-relaxed mb-4">
                        Enter the domain name you want (for example <code class="text-blue-300">mybrand.com</code> or just <code class="text-blue-300">mybrand</code>).
                        The tool will show whether the domain is available across popular TLDs such as .com, .net, .org, .io, .dev, .app, and others.
                    </p>
                    <ul class="space-y-2 text-slate-300 text-sm mb-5">
                        <li class="flex items-start gap-2">
                            <i class="fas fa-check text-emerald-400 mt-1 text-xs"></i>
                            <span><strong class="text-white">Available</strong> — you can proceed to register it</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i class="fas fa-times text-red-400 mt-1 text-xs"></i>
                            <span><strong class="text-white">Taken</strong> — try a different name or extension</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i class="fas fa-info-circle text-amber-400 mt-1 text-xs"></i>
                            <span>You can also view WHOIS details for already-registered domains</span>
                        </li>
                    </ul>
                    <p class="text-slate-500 text-sm">
                        Tip: Keep names short, memorable, and easy to spell. Avoid hyphens when possible.
                    </p>
                </div>
            </div>
        </article>

        <!-- Step 3 -->
        <article class="card step-card rounded-3xl p-7 md:p-9 transition duration-200">
            <div class="flex items-start gap-5">
                <div class="step-number w-12 h-12 rounded-2xl flex items-center justify-center text-white font-bold text-lg flex-shrink-0">3</div>
                <div class="flex-1">
                    <h3 class="section-title text-xl font-bold mb-3">Submit Domain Registration</h3>
                    <p class="text-slate-400 leading-relaxed mb-4">
                        When you find an available domain, click the registration / “Register” button next to it.
                        You will be guided through the registration form.
                    </p>
                    <div class="bg-black/40 border border-white/10 rounded-2xl p-5 mb-5">
                        <p class="text-sm font-semibold text-blue-300 mb-3">What you’ll typically provide:</p>
                        <ul class="space-y-2 text-sm text-slate-300">
                            <li class="flex gap-2"><span class="text-blue-400">•</span> Domain name confirmation</li>
                            <li class="flex gap-2"><span class="text-blue-400">•</span> Registrant contact information (name, email, address)</li>
                            <li class="flex gap-2"><span class="text-blue-400">•</span> Registration period (usually 1 year)</li>
                            <li class="flex gap-2"><span class="text-blue-400">•</span> Payment details (if required for the chosen TLD)</li>
                        </ul>
                    </div>
                    <p class="text-slate-500 text-sm">
                        WHOIS privacy is often included free of charge so your personal details stay protected.
                    </p>
                </div>
            </div>
        </article>

        <!-- Step 4 -->
        <article class="card step-card rounded-3xl p-7 md:p-9 transition duration-200">
            <div class="flex items-start gap-5">
                <div class="step-number w-12 h-12 rounded-2xl flex items-center justify-center text-white font-bold text-lg flex-shrink-0">4</div>
                <div class="flex-1">
                    <h3 class="section-title text-xl font-bold mb-3">Complete Registration & Confirm</h3>
                    <p class="text-slate-400 leading-relaxed mb-4">
                        After submitting the form and completing any required payment, you will receive a confirmation
                        (usually by email). The domain is now registered to you.
                    </p>
                    <ul class="space-y-2 text-slate-300 text-sm">
                        <li class="flex items-start gap-2">
                            <i class="fas fa-envelope text-blue-400 mt-0.5"></i>
                            <span>Check your inbox (and spam folder) for the registration confirmation</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i class="fas fa-clock text-blue-400 mt-0.5"></i>
                            <span>Propagation can take a few minutes to a few hours</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i class="fas fa-shield-alt text-blue-400 mt-0.5"></i>
                            <span>Keep your confirmation and login credentials in a safe place</span>
                        </li>
                    </ul>
                </div>
            </div>
        </article>

        <!-- Step 5 -->
        <article class="card step-card rounded-3xl p-7 md:p-9 transition duration-200">
            <div class="flex items-start gap-5">
                <div class="step-number w-12 h-12 rounded-2xl flex items-center justify-center text-white font-bold text-lg flex-shrink-0">5</div>
                <div class="flex-1">
                    <h3 class="section-title text-xl font-bold mb-3">Create Your RegisterMySite Account</h3>
                    <p class="text-slate-400 leading-relaxed mb-5">
                        Once your domain is registered, create an account (or log in) so you can start collaborating
                        with the RegisterMySite team on building your website.
                    </p>
                    <a href="https://registermysite.com/login"
                       class="cta-btn inline-flex items-center gap-2 text-white font-semibold px-5 py-3 rounded-xl transition text-sm mb-4">
                        <i class="fas fa-user-plus"></i>
                        Go to Login / Create Account
                    </a>
                    <p class="text-xs text-slate-500">
                        Link: <code class="text-blue-300">registermysite.com/login</code>
                    </p>
                    <div class="mt-5 bg-violet-500/10 border border-violet-500/20 rounded-2xl p-5">
                        <p class="text-sm text-violet-200 leading-relaxed">
                            <i class="fas fa-lightbulb mr-2"></i>
                            Having an account lets you manage your domains, choose templates, communicate with the team,
                            and track progress on your website project.
                        </p>
                    </div>
                </div>
            </div>
        </article>

        <!-- Step 6 -->
        <article class="card step-card rounded-3xl p-7 md:p-9 transition duration-200">
            <div class="flex items-start gap-5">
                <div class="step-number w-12 h-12 rounded-2xl flex items-center justify-center text-white font-bold text-lg flex-shrink-0">6</div>
                <div class="flex-1">
                    <h3 class="section-title text-xl font-bold mb-3">Collaborate with the RegisterMySite Team</h3>
                    <p class="text-slate-400 leading-relaxed mb-4">
                        After logging in, you can start working with our team to design and build your website.
                        Share your goals, brand assets, content, and any preferred style or templates.
                    </p>
                    <ul class="space-y-3 text-sm text-slate-300 mb-5">
                        <li class="flex items-start gap-3">
                            <span class="w-6 h-6 rounded-lg bg-blue-500/20 text-blue-400 flex items-center justify-center text-xs flex-shrink-0 mt-0.5">
                                <i class="fas fa-palette"></i>
                            </span>
                            <span>Browse and select from available <a href="/templates.html" class="text-blue-400 hover:underline">templates</a></span>
                        </li>
                        <li class="flex items-start gap-3">
                            <span class="w-6 h-6 rounded-lg bg-violet-500/20 text-violet-400 flex items-center justify-center text-xs flex-shrink-0 mt-0.5">
                                <i class="fas fa-comments"></i>
                            </span>
                            <span>Message the team with requirements, feedback, and revisions</span>
                        </li>
                        <li class="flex items-start gap-3">
                            <span class="w-6 h-6 rounded-lg bg-pink-500/20 text-pink-400 flex items-center justify-center text-xs flex-shrink-0 mt-0.5">
                                <i class="fas fa-upload"></i>
                            </span>
                            <span>Upload logos, images, copy, and other project assets</span>
                        </li>
                        <li class="flex items-start gap-3">
                            <span class="w-6 h-6 rounded-lg bg-emerald-500/20 text-emerald-400 flex items-center justify-center text-xs flex-shrink-0 mt-0.5">
                                <i class="fas fa-rocket"></i>
                            </span>
                            <span>Review staging previews and approve the final site</span>
                        </li>
                    </ul>
                </div>
            </div>
        </article>

        <!-- Step 7 -->
        <article class="card step-card rounded-3xl p-7 md:p-9 transition duration-200">
            <div class="flex items-start gap-5">
                <div class="step-number w-12 h-12 rounded-2xl flex items-center justify-center text-white font-bold text-lg flex-shrink-0">7</div>
                <div class="flex-1">
                    <h3 class="section-title text-xl font-bold mb-3">Launch & Manage Your Website</h3>
                    <p class="text-slate-400 leading-relaxed mb-4">
                        Once the site is ready and approved, it will be connected to your newly registered domain
                        and published live. You can continue to request updates through your account.
                    </p>
                    <div class="grid sm:grid-cols-2 gap-3 text-sm">
                        <div class="bg-black/30 border border-white/5 rounded-xl p-4">
                            <p class="font-semibold text-white mb-1">DNS & SSL</p>
                            <p class="text-slate-400">Handled for you in most cases</p>
                        </div>
                        <div class="bg-black/30 border border-white/5 rounded-xl p-4">
                            <p class="font-semibold text-white mb-1">Ongoing Updates</p>
                            <p class="text-slate-400">Request changes via your dashboard</p>
                        </div>
                        <div class="bg-black/30 border border-white/5 rounded-xl p-4">
                            <p class="font-semibold text-white mb-1">Domain Renewal</p>
                            <p class="text-slate-400">Watch for renewal notices</p>
                        </div>
                        <div class="bg-black/30 border border-white/5 rounded-xl p-4">
                            <p class="font-semibold text-white mb-1">Support</p>
                            <p class="text-slate-400">Email <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="057664696076457760626c76716077687c766c71602b666a68">[email&#160;protected]</a></p>
                        </div>
                    </div>
                </div>
            </div>
        </article>
    </section>

    <!-- Helpful Links -->
    <section class="max-w-3xl mx-auto px-6 pb-16">
        <div class="card rounded-3xl p-8 md:p-10 text-center">
            <h2 class="section-title text-2xl font-bold mb-3">
                Ready to <span class="gradient-text">Get Started?</span>
            </h2>
            <p class="text-slate-400 mb-8 max-w-lg mx-auto">
                Begin by searching for your ideal domain name, then follow the steps above to register and build.
            </p>
            <div class="flex flex-col sm:flex-row gap-4 justify-center">
                <a href="https://registermysite.com/tools/Domain_Search"
                   class="cta-btn inline-flex items-center justify-center gap-2 text-white font-semibold px-7 py-4 rounded-2xl transition">
                    <i class="fas fa-search"></i>
                    Search Domains
                </a>
                <a href="https://registermysite.com/login"
                   class="inline-flex items-center justify-center gap-2 bg-white/5 hover:bg-white/10 border border-white/15 text-white font-semibold px-7 py-4 rounded-2xl transition">
                    <i class="fas fa-sign-in-alt"></i>
                    Login / Create Account
                </a>
            </div>
        </div>
    </section>

    <!-- FAQ-style notes -->
    <section class="max-w-3xl mx-auto px-6 pb-20">
        <h2 class="section-title text-2xl font-bold mb-6 text-center">Additional Notes</h2>
        <div class="space-y-4">
            <div class="card rounded-2xl p-6">
                <h3 class="font-semibold text-white mb-2 flex items-center gap-2">
                    <i class="fas fa-question-circle text-blue-400"></i>
                    What if the domain I want is taken?
                </h3>
                <p class="text-slate-400 text-sm leading-relaxed">
                    Try alternative spellings, different TLDs (.io, .dev, .app, .co, etc.), or add a short keyword
                    (e.g. getmybrand.com). You can also check the aftermarket later if the domain becomes available.
                </p>
            </div>
            <div class="card rounded-2xl p-6">
                <h3 class="font-semibold text-white mb-2 flex items-center gap-2">
                    <i class="fas fa-lock text-blue-400"></i>
                    Is WHOIS privacy included?
                </h3>
                <p class="text-slate-400 text-sm leading-relaxed">
                    In most cases yes. Privacy protection helps keep your personal contact information out of public WHOIS records.
                    Confirm the exact details during registration.
                </p>
            </div>
            <div class="card rounded-2xl p-6">
                <h3 class="font-semibold text-white mb-2 flex items-center gap-2">
                    <i class="fas fa-headset text-blue-400"></i>
                    Need help?
                </h3>
                <p class="text-slate-400 text-sm leading-relaxed">
                    Contact the team at <a href="/cdn-cgi/l/email-protection#3340525f5640734156545a404756415e4a405a47561d505c5e" class="text-blue-400 hover:underline"><span class="__cf_email__" data-cfemail="7102101d14023103141618020514031c08021805145f121e1c">[email&#160;protected]</span></a>
                    for assistance with registration, account setup, or website collaboration.
                </p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="border-t border-white/10 py-12">
        <div class="max-w-4xl mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-6 text-sm text-slate-500">
            <div class="flex items-center gap-2">
                <div class="w-8 h-8 rounded-lg bg-gradient-to-br from-blue-500 to-violet-600 flex items-center justify-center font-bold text-white text-sm">R</div>
                <span>registermysite.com</span>
            </div>
            <p>© 2026 registermysite.com — Documentation</p>
            <p class="italic">You dream. We code.</p>
        </div>
        <p class="text-center text-xs text-slate-600 mt-6 max-w-2xl mx-auto px-6">
            Domain registration and website collaboration services provided by registermysite.com •
            For assistance email <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="0774666b6274477562606e747362756a7e746e73622964686a">[email&#160;protected]</a>
        </p>
    </footer>

<script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script></body>
</html></doc><doc title="API Reference" desc="Endpoints for authentication (Google/GitHub) and more"><!DOCTYPE html>
<html lang="en">
<head>
  <!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-GMLQJKKPPP"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-GMLQJKKPPP');
</script>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>API Reference — registermysite.com</title>
  <meta name="description" content="RegisterMySite API reference: authentication, domain tools, checkout, health, and dashboard endpoints." />
  <link rel="canonical" href="https://registermysite.com/api" />

  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Space+Grotesk:wght@500;600;700&display=swap');

    body {
      font-family: 'Inter', system-ui, sans-serif;
      background: #0a0a0f;
      color: #e2e8f0;
    }

    .section-title {
      font-family: 'Space Grotesk', sans-serif;
    }

    .gradient-text {
      background: linear-gradient(135deg, #60a5fa, #a78bfa, #f472b6);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .card {
      background: rgba(255, 255, 255, 0.03);
      border: 1px solid rgba(255, 255, 255, 0.08);
    }

    .method {
      font-family: ui-monospace, SFMono-Regular, Menlo, monospace;
      font-size: 0.7rem;
      font-weight: 700;
      letter-spacing: 0.04em;
      padding: 0.2rem 0.5rem;
      border-radius: 6px;
      text-transform: uppercase;
    }

    .method-get { background: rgba(52, 211, 153, 0.15); color: #6ee7b7; }
    .method-post { background: rgba(96, 165, 250, 0.15); color: #93c5fd; }
    .method-put { background: rgba(251, 191, 36, 0.15); color: #fcd34d; }
    .method-delete { background: rgba(248, 113, 113, 0.15); color: #fca5a5; }

    .path {
      font-family: ui-monospace, SFMono-Regular, Menlo, monospace;
      font-size: 0.85rem;
      color: #e2e8f0;
    }

    pre.code-block {
      background: #050508;
      border: 1px solid rgba(255, 255, 255, 0.1);
      border-radius: 12px;
      padding: 1rem 1.1rem;
      overflow-x: auto;
      font-size: 0.75rem;
      line-height: 1.55;
      color: #cbd5e1;
    }

    pre.code-block .key { color: #7dd3fc; }
    pre.code-block .str { color: #86efac; }
    pre.code-block .num { color: #fcd34d; }
    pre.code-block .comment { color: #64748b; }
  </style>
</head>
<body class="min-h-screen">

  <!-- Header -->
  <header class="border-b border-white/10 sticky top-0 z-50 backdrop-blur-xl bg-black/60">
    <div class="max-w-5xl mx-auto px-6 py-5 flex items-center justify-between">
      <a href="/" class="flex items-center gap-3">
        <div class="w-10 h-10 rounded-xl bg-gradient-to-br from-blue-500 to-violet-600 flex items-center justify-center font-bold text-white text-lg">R</div>
        <div>
          <span class="text-xl font-bold tracking-tight">registermysite</span><span class="text-blue-400">.com</span>
        </div>
      </a>
      <nav class="hidden sm:flex items-center gap-6 text-sm font-medium">
        <a href="/docs" class="hover:text-blue-400 transition">Docs</a>
        <a href="/api" class="text-blue-400">API</a>
        <a href="/tools" class="hover:text-blue-400 transition">Tools</a>
        <a href="/login" class="hover:text-blue-400 transition">Login</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="max-w-5xl mx-auto px-6 pt-16 pb-10 text-center">
    <h1 class="section-title text-4xl md:text-5xl font-bold mb-4">
      API <span class="gradient-text">Reference</span>
    </h1>
    <p class="text-slate-400 text-lg max-w-2xl mx-auto leading-relaxed">
      Endpoints powering authentication, domain workflows, subscriptions, and account data
      on RegisterMySite. Base URL depends on your deployment host.
    </p>
  </section>

  <!-- Base info -->
  <section class="max-w-5xl mx-auto px-6 pb-12">
    <div class="card rounded-2xl p-6 md:p-8 grid md:grid-cols-3 gap-6 text-sm">
      <div>
        <div class="text-slate-500 text-xs uppercase tracking-wide mb-1">Base URL</div>
        <code class="text-blue-300 text-sm break-all">https://registermysite.com</code>
      </div>
      <div>
        <div class="text-slate-500 text-xs uppercase tracking-wide mb-1">Format</div>
        <p class="text-slate-300">JSON request &amp; response bodies</p>
      </div>
      <div>
        <div class="text-slate-500 text-xs uppercase tracking-wide mb-1">Auth</div>
        <p class="text-slate-300">Session cookie or Bearer token where noted</p>
      </div>
    </div>
  </section>

  <!-- Auth -->
  <section class="max-w-5xl mx-auto px-6 pb-14">
    <h2 class="section-title text-2xl font-bold mb-6">Authentication</h2>
    <div class="space-y-4">

      <article class="card rounded-2xl p-5 md:p-6">
        <div class="flex flex-wrap items-center gap-3 mb-3">
          <span class="method method-get">GET</span>
          <span class="path">/api/auth/google</span>
        </div>
        <p class="text-sm text-slate-400 mb-3">Start Google OAuth. Redirects the browser to Google, then back to the callback.</p>
        <p class="text-xs text-slate-500">No body. Sets short-lived OAuth <code class="text-slate-400">state</code> in KV.</p>
      </article>

      <article class="card rounded-2xl p-5 md:p-6">
        <div class="flex flex-wrap items-center gap-3 mb-3">
          <span class="method method-get">GET</span>
          <span class="path">/api/auth/github</span>
        </div>
        <p class="text-sm text-slate-400 mb-3">Start GitHub OAuth. Same pattern as Google with GitHub authorize URL.</p>
      </article>

      <article class="card rounded-2xl p-5 md:p-6">
        <div class="flex flex-wrap items-center gap-3 mb-3">
          <span class="method method-get">GET</span>
          <span class="path">/api/auth/callback/google</span>
        </div>
        <p class="text-sm text-slate-400 mb-3">OAuth callback. Query: <code class="text-slate-300">code</code>, <code class="text-slate-300">state</code>. Creates/finds user in D1, opens Durable Object session, sets <code class="text-slate-300">session</code> cookie, redirects to <code class="text-slate-300">/dashboard</code>.</p>
      </article>

      <article class="card rounded-2xl p-5 md:p-6">
        <div class="flex flex-wrap items-center gap-3 mb-3">
          <span class="method method-get">GET</span>
          <span class="path">/api/auth/callback/github</span>
        </div>
        <p class="text-sm text-slate-400">GitHub OAuth callback — same session flow as Google.</p>
      </article>

      <article class="card rounded-2xl p-5 md:p-6">
        <div class="flex flex-wrap items-center gap-3 mb-3">
          <span class="method method-get">GET</span>
          <span class="path">/api/auth/me</span>
        </div>
        <p class="text-sm text-slate-400 mb-3">Current user from session cookie. <code class="text-slate-300">401</code> if logged out.</p>
        <pre class="code-block">{
  <span class="key">"user"</span>: {
    <span class="key">"id"</span>: <span class="str">"uuid"</span>,
    <span class="key">"email"</span>: <span class="str">"<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="1c6573695c79647d716c7079327f7371">[email&#160;protected]</a>"</span>,
    <span class="key">"name"</span>: <span class="str">"Jane Doe"</span>,
    <span class="key">"avatar_url"</span>: <span class="str">"https://…"</span>,
    <span class="key">"provider"</span>: <span class="str">"google"</span>
  }
}</pre>
      </article>

      <article class="card rounded-2xl p-5 md:p-6">
        <div class="flex flex-wrap items-center gap-3 mb-3">
          <span class="method method-post">POST</span>
          <span class="path">/api/auth/logout</span>
        </div>
        <p class="text-sm text-slate-400">Destroys Durable Object session and clears the <code class="text-slate-300">session</code> cookie.</p>
      </article>
    </div>
  </section>

  <!-- Dashboard -->
  <section class="max-w-5xl mx-auto px-6 pb-14">
    <h2 class="section-title text-2xl font-bold mb-6">Dashboard</h2>
    <article class="card rounded-2xl p-5 md:p-6">
      <div class="flex flex-wrap items-center gap-3 mb-3">
        <span class="method method-get">GET</span>
        <span class="path">/api/dashboard</span>
      </div>
      <p class="text-sm text-slate-400 mb-3">Protected. Requires valid session. Returns welcome payload and user profile for the dashboard UI.</p>
      <pre class="code-block">{
  <span class="key">"message"</span>: <span class="str">"Welcome back, Jane!"</span>,
  <span class="key">"user"</span>: { <span class="key">"id"</span>: <span class="str">"…"</span>, <span class="key">"email"</span>: <span class="str">"…"</span>, <span class="key">"name"</span>: <span class="str">"…"</span>, <span class="key">"provider"</span>: <span class="str">"github"</span> }
}</pre>
    </article>
  </section>

  <!-- Checkout -->
  <section class="max-w-5xl mx-auto px-6 pb-14">
    <h2 class="section-title text-2xl font-bold mb-6">Checkout &amp; billing</h2>
    <article class="card rounded-2xl p-5 md:p-6">
      <div class="flex flex-wrap items-center gap-3 mb-3">
        <span class="method method-post">POST</span>
        <span class="path">/api/checkout/create-subscription</span>
      </div>
      <p class="text-sm text-slate-400 mb-3">
        Creates a subscription for a pricing plan. Body fields from the checkout form.
        Integrate with Stripe (or similar) on the server; return <code class="text-slate-300">clientSecret</code> or <code class="text-slate-300">redirectUrl</code>.
      </p>
      <p class="text-xs text-slate-500 mb-2">Request body</p>
      <pre class="code-block">{
  <span class="key">"plan"</span>: <span class="str">"starter"</span> | <span class="str">"growth"</span> | <span class="str">"pro"</span>,
  <span class="key">"firstName"</span>: <span class="str">"Jane"</span>,
  <span class="key">"lastName"</span>: <span class="str">"Doe"</span>,
  <span class="key">"email"</span>: <span class="str">"<a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="dbb1bab5be9bb8b4b6abbab5a2f5b8b4b6">[email&#160;protected]</a>"</span>,
  <span class="key">"company"</span>: <span class="str">"Acme"</span> | <span class="num">null</span>,
  <span class="key">"country"</span>: <span class="str">"US"</span>,
  <span class="key">"postal"</span>: <span class="str">"90210"</span>
}</pre>
      <p class="text-xs text-slate-500 mt-3 mb-2">Plans</p>
      <div class="grid sm:grid-cols-3 gap-3 text-sm">
        <div class="rounded-xl bg-black/30 border border-white/10 p-3"><strong class="text-white">starter</strong> — $49/mo</div>
        <div class="rounded-xl bg-black/30 border border-white/10 p-3"><strong class="text-white">growth</strong> — $129/mo</div>
        <div class="rounded-xl bg-black/30 border border-white/10 p-3"><strong class="text-white">pro</strong> — $299/mo</div>
      </div>
    </article>
  </section>

  <!-- Domain / tools notes -->
  <section class="max-w-5xl mx-auto px-6 pb-14">
    <h2 class="section-title text-2xl font-bold mb-6">Domain &amp; tools</h2>
    <div class="card rounded-2xl p-5 md:p-6 space-y-4 text-sm text-slate-400">
      <p>
        Interactive domain search and WHOIS-style checks are primarily implemented in the
        <a href="/tools/Domain_Search" class="text-blue-400 hover:underline">Domain Search</a> UI
        (including client-side availability checks). Server-side registration handoff can target:
      </p>
      <div class="flex flex-wrap items-center gap-3">
        <span class="method method-get">GET</span>
        <span class="path">/register?domain={name}</span>
      </div>
      <p>
        Additional tool pages (QR, TLD search, payments demos) are served as static/app routes under
        <code class="text-slate-300">/tools/…</code>. Extend this reference as you expose dedicated JSON endpoints for those tools.
      </p>
    </div>
  </section>

  <!-- Health -->
  <section class="max-w-5xl mx-auto px-6 pb-14">
    <h2 class="section-title text-2xl font-bold mb-6">System</h2>
    <article class="card rounded-2xl p-5 md:p-6">
      <div class="flex flex-wrap items-center gap-3 mb-3">
        <span class="method method-get">GET</span>
        <span class="path">/api/health</span>
      </div>
      <p class="text-sm text-slate-400 mb-3">Liveness check for monitoring and deploy verification.</p>
      <pre class="code-block">{
  <span class="key">"ok"</span>: <span class="num">true</span>,
  <span class="key">"timestamp"</span>: <span class="str">"2026-07-26T11:00:00.000Z"</span>
}</pre>
    </article>
  </section>

  <!-- Errors -->
  <section class="max-w-5xl mx-auto px-6 pb-14">
    <h2 class="section-title text-2xl font-bold mb-6">Errors</h2>
    <div class="card rounded-2xl p-6 overflow-x-auto">
      <table class="w-full text-sm text-left">
        <thead>
          <tr class="text-slate-500 border-b border-white/10">
            <th class="py-2 pr-4 font-medium">Status</th>
            <th class="py-2 font-medium">Meaning</th>
          </tr>
        </thead>
        <tbody class="text-slate-300">
          <tr class="border-b border-white/5"><td class="py-2.5 pr-4 font-mono text-xs">400</td><td>Missing or invalid parameters</td></tr>
          <tr class="border-b border-white/5"><td class="py-2.5 pr-4 font-mono text-xs">401</td><td>Not authenticated / invalid session</td></tr>
          <tr class="border-b border-white/5"><td class="py-2.5 pr-4 font-mono text-xs">403</td><td>Authenticated but not allowed</td></tr>
          <tr class="border-b border-white/5"><td class="py-2.5 pr-4 font-mono text-xs">404</td><td>Route or resource not found</td></tr>
          <tr><td class="py-2.5 pr-4 font-mono text-xs">500</td><td>Server error (check Worker logs)</td></tr>
        </tbody>
      </table>
      <p class="text-xs text-slate-500 mt-4">Error bodies typically include <code class="text-slate-400">{"message": "…"}</code>.</p>
    </div>
  </section>

  <!-- Stack note -->
  <section class="max-w-5xl mx-auto px-6 pb-16">
    <div class="card rounded-2xl p-6 text-sm text-slate-400">
      <h3 class="font-semibold text-white mb-2">Infrastructure</h3>
      <p class="leading-relaxed">
        APIs run on <strong class="text-slate-200">Cloudflare Workers</strong> with
        <strong class="text-slate-200">D1</strong> (users), <strong class="text-slate-200">KV</strong> (OAuth state),
        and <strong class="text-slate-200">Durable Objects</strong> (sessions). Deploy and manage with
        <code class="text-slate-300">wrangler</code>. You own the project code and data bindings in your account.
      </p>
    </div>
  </section>

  <!-- CTA -->
  <section class="max-w-5xl mx-auto px-6 pb-20">
    <div class="card rounded-3xl p-10 text-center">
      <h2 class="section-title text-2xl font-bold mb-3">Building on RegisterMySite?</h2>
      <p class="text-slate-400 max-w-lg mx-auto mb-8 text-sm">
        Need a custom endpoint for domains, billing webhooks, or your client dashboard?
        We implement APIs in-house and hand off the source.
      </p>
      <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
        <a href="/contact" class="inline-flex items-center gap-2 bg-gradient-to-r from-blue-500 to-violet-600 text-white font-semibold px-6 py-3.5 rounded-xl transition hover:from-blue-400 hover:to-violet-500">
          Contact Us
        </a>
        <a href="/docs" class="inline-flex items-center gap-2 border border-white/15 hover:border-white/30 font-semibold px-6 py-3.5 rounded-xl transition">
          Read Docs
        </a>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="border-t border-white/10 py-10">
    <div class="max-w-5xl mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-4 text-sm text-slate-500">
      <div class="flex items-center gap-2">
        <div class="w-8 h-8 rounded-lg bg-gradient-to-br from-blue-500 to-violet-600 flex items-center justify-center font-bold text-white text-sm">R</div>
        <span>registermysite.com</span>
      </div>
      <p>© 2026 registermysite.com</p>
      <p class="italic">You dream. We code.</p>
    </div>
  </footer>

<script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script></body>
</html></doc></core pages><services><doc title="Domain &amp; DNS Setup" desc="Register or connect domains, configure DNS"><!DOCTYPE html>
<html lang="en">
<head>

  <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence</title>
    <meta name="description" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">
    <meta name="title" content="RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <!-- Preconnect to the domain-->
    <link rel="preconnect" href="https://visitor-counter.registermysite.com" crossorigin>
    <!-- Optional: Preload the script for even faster loading -->
    <link rel="preload" href="https://visitor-counter.registermysite.com/widget.js" as="script">
  <!-- Favicons and install icons -->
  <link rel="icon" href="/assets/icons/favicon.ico" sizes="any">
  <link rel="icon" type="image/png" sizes="16x16" href="/assets/icons/favicon-16x16.jpg">
  <link rel="icon" type="image/png" sizes="32x32" href="/assets/icons/favicon-32x32.jpg">
  <link rel="icon" type="image/png" sizes="48x48" href="/assets/icons/favicon-48x48.jpg">
  <link rel="icon" type="image/png" sizes="96x96" href="/assets/icons/favicon-96x96.jpg">
  <link rel="apple-touch-icon" sizes="180x180" href="/assets/icons/apple-touch-icon.jpg">
  <link rel="manifest" href="/assets/manifest.json">

  <!-- Open Graph / Facebook -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://registermysite.com">
  <meta property="og:title" content="RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence">
  <meta property="og:description" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">
  <meta property="og:image" content="https://registermysite.com/assets/og-card.jpg">
  <meta property="og:image:width" content="1200">
  <meta property="og:image:height" content="630">
  <meta property="og:image:alt" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">

  <!-- Twitter -->
  <meta property="twitter:card" content="summary_large_image">
  <meta property="twitter:url" content="https://registermysite.com">
  <meta property="twitter:title" content="RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence">
  <meta property="twitter:description" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">
  <meta property="twitter:image" content="https://registermysite.com/assets/og-card.jpg">

  <!-- Structured data -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "WebApplication",
    "name": "Register My Site",
    "url": "https://registermysite.com",
    "description": "RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.",
    "applicationCategory": "UtilitiesApplication",
    "operatingSystem": "Any (Windows, macOS, Android, iOS, Linux, ChromeOS)",
    "isAccessibleForFree": true,
    "offers": {
      "@type": "Offer",
      "price": "0",
      "priceCurrency": "USD"
    }
  }
  </script>

  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Space+Grotesk:wght@500;600;700&display=swap');

    body {
      font-family: 'Inter', system-ui, sans-serif;
      background: #0a0a0f;
      color: #e2e8f0;
    }

    .section-title {
      font-family: 'Space Grotesk', sans-serif;
    }

    .gradient-text {
      background: linear-gradient(135deg, #60a5fa, #a78bfa, #f472b6);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }

    .card {
      background: rgba(255, 255, 255, 0.03);
      border: 1px solid rgba(255, 255, 255, 0.08);
      transition: border-color 0.2s, background 0.2s;
    }

    .card:hover {
      border-color: rgba(96, 165, 250, 0.28);
      background: rgba(255, 255, 255, 0.045);
    }

    /* Hero background image + overlay */
    .hero {
            background: linear-gradient(rgba(0,123,255,0.88), rgba(0,80,200,0.88)), url('https://uploads.registermysite.com/registermysite.gif?auto=format&fit=crop&w=1920&q=80') center/cover no-repeat;
            color: white;
            text-align: center;
            padding: 160px 20px 120px;
            position: relative;
        }

    .cta-primary {
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: #fff;
      transition: background 0.25s ease, transform 0.2s ease, box-shadow 0.25s ease;
    }

    .cta-primary {
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: #fff;
      transition: background 0.25s ease, transform 0.2s ease, box-shadow 0.25s ease;
    }

    .cta-primary:hover {
      background: linear-gradient(135deg, #22d3ee, #a78bfa);
      transform: translateY(-2px);
      box-shadow: 0 12px 32px rgba(96, 165, 250, 0.35);
    }

    .cta-secondary {
      background: transparent;
      color: #e2e8f0;
      border: 1px solid rgba(255, 255, 255, 0.2);
      transition: background 0.25s ease, border-color 0.25s ease, color 0.25s ease, transform 0.2s ease;
    }

    .cta-secondary:hover {
      background: rgba(96, 165, 250, 0.15);
      border-color: #60a5fa;
      color: #93c5fd;
      transform: translateY(-2px);
    }

    /* Domain search bar */
    .domain-search-wrap {
      display: flex;
      flex-direction: column;
      gap: 0.75rem;
      width: 100%;
      max-width: 36rem;
    }

    @media (min-width: 640px) {
      .domain-search-wrap {
        flex-direction: row;
        align-items: stretch;
      }
    }

    .domain-search-input {
      flex: 1;
      background: rgba(0, 0, 0, 0.55);
      border: 1px solid rgba(255, 255, 255, 0.14);
      color: #e2e8f0;
      border-radius: 12px;
      padding: 0.9rem 1.1rem;
      font-size: 1rem;
      transition: border-color 0.2s, box-shadow 0.2s;
      min-width: 0;
    }

    .domain-search-input:focus {
      outline: none;
      border-color: #60a5fa;
      box-shadow: 0 0 0 3px rgba(96, 165, 250, 0.2);
    }

    .domain-search-input::placeholder {
      color: #64748b;
    }

    .domain-search-btn {
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: #fff;
      border: none;
      border-radius: 12px;
      padding: 0.9rem 1.4rem;
      font-weight: 600;
      font-size: 0.95rem;
      cursor: pointer;
      white-space: nowrap;
      transition: background 0.25s ease, transform 0.2s ease, box-shadow 0.25s ease;
    }

    .domain-search-btn:hover:not(:disabled) {
      background: linear-gradient(135deg, #22d3ee, #a78bfa);
      transform: translateY(-1px);
      box-shadow: 0 10px 28px rgba(96, 165, 250, 0.35);
    }

    .domain-search-btn:disabled {
      opacity: 0.65;
      cursor: wait;
    }

    /* Result modal */
    .domain-modal-backdrop {
      position: fixed;
      inset: 0;
      background: rgba(0, 0, 0, 0.7);
      backdrop-filter: blur(6px);
      z-index: 100;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 1.25rem;
      opacity: 0;
      visibility: hidden;
      transition: opacity 0.2s ease, visibility 0.2s ease;
    }

    .domain-modal-backdrop.open {
      opacity: 1;
      visibility: visible;
    }

    .domain-modal {
      background: #12121a;
      border: 1px solid rgba(255, 255, 255, 0.12);
      border-radius: 1.25rem;
      padding: 1.75rem 1.5rem;
      width: 100%;
      max-width: 26rem;
      box-shadow: 0 24px 64px rgba(0, 0, 0, 0.5);
      transform: translateY(12px);
      transition: transform 0.2s ease;
    }

    .domain-modal-backdrop.open .domain-modal {
      transform: translateY(0);
    }

    /* Mobile menu */
    .mobile-panel {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.35s ease;
    }

    .mobile-panel.open {
      max-height: 640px;
    }

    .mobile-sub {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.3s ease;
    }

    .mobile-sub.open {
      max-height: 280px;
    }

    .nav-link {
      transition: color 0.15s ease;
    }

    .nav-link:hover {
      color: #60a5fa;
    }

    .status-pill {
      display: inline-flex;
      align-items: center;
      gap: 0.35rem;
      font-size: 0.75rem;
      padding: 0.35rem 0.7rem;
      border-radius: 9999px;
      background: rgba(16, 185, 129, 0.12);
      border: 1px solid rgba(16, 185, 129, 0.25);
      color: #6ee7b7;
    }

    .step-num {
      width: 2.25rem;
      height: 2.25rem;
      border-radius: 9999px;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      font-weight: 700;
      font-size: 0.9rem;
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: white;
      flex-shrink: 0;
    }
    .logo-circle {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 36px;          /* tiny size */
  height: 36px;
  border-radius: 50%;   /* makes it a circle */
  overflow: hidden;     /* clips the image to the circle */
  background: white;    /* optional fallback */
  border: 2px solid rgba(255,255,255,0.3);
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}

.logo-circle img {
  width: 100%;
  height: 100%;
  object-fit: cover;    /* fills the circle nicely */
}

.logo-circle:hover {
  transform: scale(1.08);
  box-shadow: 0 0 0 3px rgba(79, 70, 229, 0.3);
}
  </style>
   <!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-GMLQJKKPPP"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-GMLQJKKPPP');
</script>
</head>
<body class="min-h-screen">

  <!-- ========== NAVIGATION ========== -->
  <header class="border-b border-white/10 sticky top-0 z-50 backdrop-blur-xl bg-black/70">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="flex items-center justify-between h-16">
        <!-- Logo -->
        <a href="/" class="flex items-center gap-3 shrink-0">
          <img src="https://uploads.registermysite.com/registermysite.gif" alt="Logo" class="h-10 w-10 rounded-xl object-cover bg-white/20">
        <div>
         <span class="text-2xl font-bold tracking-tight">RegisterMySite</span><span class="text-blue-400">.com</span>
          </div>
        </a>

        <!-- Desktop nav -->
        <nav class="hidden lg:flex items-center gap-7 text-sm font-medium">
          <a href="/services" class="nav-link text-slate-300">Services</a>
          <a href="/pricing" class="nav-link text-slate-300">Pricing</a>
          <div class="relative group">
            <button type="button" class="nav-link text-slate-300 inline-flex items-center gap-1.5">
              Tools <i class="fas fa-chevron-down text-[10px] opacity-70"></i>
            </button>
            <div class="invisible opacity-0 group-hover:visible group-hover:opacity-100 transition-all duration-200 absolute top-full left-0 pt-2 w-56">
              <div class="card rounded-xl py-2 shadow-xl shadow-black/40">
                <a href="/tools/Domain_Search" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">Domain Search</a>
                <a href="/tools/TLDsearch" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">TLD Search</a>
                <a href="/tools/QR_Code" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">QR Code</a>
                <a href="/tools/og-preview" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">OG Preview</a>
                <a href="https://meta-gen.registermysite.com" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">Meta Generator</a>
                <a href="https://email-gen.registermysite.com" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">Email Template Generator</a>
                <a href="https://ai.editor.registermysite.com" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">HTML Website Generator</a>
                <a href="/tools" class="block px-4 py-2.5 text-sm text-blue-400 hover:bg-white/5 border-t border-white/10 mt-1 pt-2.5">All tools →</a>
              </div>
            </div>
          </div>
          <a href="/Web_Design" class="nav-link text-slate-300">Web Design</a>
          <a href="/Business_Email.html" class="nav-link text-slate-300">Business Email</a>
          <a href="/docs" class="nav-link text-slate-300">Docs</a>
          <a href="/contact" class="nav-link text-slate-300">Contact</a>
          <a href="/login" class="cta-primary text-sm font-semibold px-4 py-2 rounded-lg">Login</a>
        </nav>

        <!-- Mobile hamburger -->
        <button type="button" id="menu-btn" class="lg:hidden w-10 h-10 flex items-center justify-center rounded-lg border border-white/10 text-slate-200 hover:border-blue-400/40" aria-label="Open menu" aria-expanded="false">
          <i class="fas fa-bars text-lg" id="menu-icon"></i>
        </button>
      </div>

      <!-- Mobile dropdown panel -->
      <div id="mobile-menu" class="mobile-panel lg:hidden border-t border-white/10">
        <nav class="py-3 flex flex-col text-sm font-medium">
          <a href="/services" class="px-2 py-3 text-slate-300 hover:text-blue-400">Services</a>
          <a href="/pricing" class="px-2 py-3 text-slate-300 hover:text-blue-400">Pricing</a>

          <!-- Expandable: Tools -->
          <button type="button" id="tools-toggle" class="px-2 py-3 text-left text-slate-300 hover:text-blue-400 flex items-center justify-between w-full">
            <span>Tools</span>
            <i class="fas fa-chevron-down text-xs transition-transform duration-200" id="tools-chevron"></i>
          </button>
          <div id="tools-sub" class="mobile-sub bg-black/30 rounded-xl mx-1 mb-1">
            <a href="/tools/Domain_Search" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">Domain Search</a>
            <a href="/tools/TLDsearch" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">TLD Search</a>
            <a href="/tools/QR_Code" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">QR Code Generator</a>
            <a href="/tools/og-image" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">OG Image Generator</a>
            <a href="/tools/og-preview" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">OG Preview</a>
            <a href="https://meta-gen.registermysite.com" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">Meta Title Generator</a>
            <a href="https://email-gen.registermysite.com" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">Email Template Generator</a>
            <a href="https://ai.editor.registermysite.com" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">HTML Website Generator</a>
            <a href="/tools" class="block px-4 py-2.5 text-blue-400 hover:text-blue-300">View all tools →</a>
          </div>

          <a href="/Web_Design" class="px-2 py-3 text-slate-300 hover:text-blue-400">Web Design</a>
          <a href="/SEO_Optimization" class="px-2 py-3 text-slate-300 hover:text-blue-400">SEO</a>
          <a href="/Business_Email" class="px-2 py-3 text-slate-300 hover:text-blue-400">Business Email</a>
          <a href="/docs" class="px-2 py-3 text-slate-300 hover:text-blue-400">Docs</a>
          <a href="/contact" class="px-2 py-3 text-slate-300 hover:text-blue-400">Contact</a>
          <a href="/login" class="mx-2 mt-2 mb-3 cta-primary text-center font-semibold py-3 rounded-xl">Login / Sign up</a>
        </nav>
      </div>
    </div>
  </header>

  <!-- ========== HERO ========== -->
  <section class="hero">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-24 w-full relative z-10">
      <p class="text-blue-400 text-sm font-semibold tracking-wide uppercase mb-4">Web development agency</p>
      <h1 class="section-title text-4xl sm:text-5xl md:text-6xl font-bold leading-tight mb-5 max-w-3xl">
        Your Business <span class="gradient-text">Online</span>
      </h1>
      <p class="text-slate-300 text-lg md:text-xl max-w-2xl leading-relaxed mb-8">
        Multi-platform presence that ties your website, Google Business, Yelp, and social profiles together —
        so customers find a professional brand, not scattered listings.
      </p>

      <form id="hero-domain-form" class="domain-search-wrap mb-4" autocomplete="off">
        <input
          type="text"
          id="hero-domain-input"
          class="domain-search-input"
          placeholder="Search a domain — e.g. example.com"
          spellcheck="false"
          autocapitalize="off"
          inputmode="url"
          aria-label="Domain name to search"
        />
        <button type="submit" id="hero-domain-btn" class="domain-search-btn">
          <i class="fas fa-search mr-1.5"></i> Search
        </button>
      </form>
      <p id="hero-domain-hint" class="text-sm text-slate-500 mb-6 min-h-[1.25rem]"></p>

      <div class="flex flex-col sm:flex-row gap-3 sm:gap-4 mb-10">
        <a href="/contact" class="cta-secondary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl text-base">
          <i class="fas fa-envelope"></i>
          Contact Us Today
        </a>
        <a href="/tools/Domain_Search" class="cta-secondary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl text-base text-sm">
          Advanced domain tools →
        </a>
      </div>

      <!-- Platform status pills -->
      <div class="flex flex-wrap gap-2">
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Yelp · Claimed &amp; Linked</span>
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Google Business · Claimed &amp; Linked</span>
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Facebook · Connected</span>
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Instagram · Connected</span>
      </div>
    </div>
  </section>

  <!-- ========== CORE SERVICES ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-20">
    <div class="text-center mb-12">
      <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
        Everything Your Business Needs <span class="gradient-text">Online</span>
      </h2>
      <p class="text-slate-400 text-base md:text-lg max-w-2xl mx-auto leading-relaxed">
        From domain setup to SEO-powered websites and professional email — we handle the technical side
        so you can focus on customers.
      </p>
    </div>

    <div class="grid sm:grid-cols-2 gap-5">
      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-blue-500/15 text-blue-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-globe"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">Domain &amp; DNS Setup</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          We register or connect your domain, configure DNS records correctly, and make sure everything
          points to your new site with zero downtime.
        </p>
      </article>

      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-violet-500/15 text-violet-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-magnifying-glass"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">SEO Optimization</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Technical SEO, schema markup, local SEO, and strategic linking of all your platform profiles
          so Google ranks your business higher.
        </p>
      </article>

      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-pink-500/15 text-pink-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-palette"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">Web Design &amp; Templates</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Beautiful, conversion-focused designs and ready-to-use industry templates. Fully responsive
          and mobile-first for every device.
        </p>
      </article>

      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-emerald-500/15 text-emerald-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-envelope"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">Custom Business Email</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Professional email addresses (@yourbusiness.com) with auto-reply workers that respond
          instantly while you’re busy with customers.
        </p>
      </article>
    </div>
  </section>

  <!-- ========== HOW IT WORKS ========== -->
  <section class="border-y border-white/5 bg-white/[0.015]">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-20">
      <div class="text-center mb-12">
        <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
          How It <span class="gradient-text">Works</span>
        </h2>
        <p class="text-slate-400 max-w-xl mx-auto">
          From scattered listings to a fully connected online presence in four simple steps.
        </p>
      </div>

      <div class="grid md:grid-cols-2 gap-5">
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">1</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Audit Your Listings</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              We find every unclaimed or disconnected profile for your business across major platforms.
            </p>
          </div>
        </div>
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">2</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Build Your Website</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              Choose a template or go custom. We create a site that showcases your business and services.
            </p>
          </div>
        </div>
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">3</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Claim &amp; Link Everything</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              We claim your Yelp, Google Business, and other accounts and link them back to your new website.
            </p>
          </div>
        </div>
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">4</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Launch &amp; Rank</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              DNS, SEO, emails, and analytics go live. Your business becomes discoverable and professional.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ========== TOOLS ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-20">
    <div class="text-center mb-12">
      <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
        Built for Developers &amp; <span class="gradient-text">Businesses</span>
      </h2>
      <p class="text-slate-400 max-w-xl mx-auto">
        Powerful tools when you need them, simple when you don’t.
      </p>
    </div>

    <div class="grid md:grid-cols-3 gap-5">
      <article class="card rounded-2xl p-6">
        <div class="text-blue-400 text-xl mb-3"><i class="fas fa-file-lines"></i></div>
        <h3 class="font-semibold text-lg mb-2">Templates</h3>
        <p class="text-sm text-slate-400 leading-relaxed mb-4">
          Browse dozens of industry-ready website templates. Restaurants, salons, contractors, clinics —
          pick one and customize in minutes.
        </p>
        <a href="/templates" class="text-sm text-blue-400 hover:text-blue-300 font-medium">Browse templates →</a>
      </article>
      <article class="card rounded-2xl p-6">
        <div class="text-violet-400 text-xl mb-3"><i class="fas fa-bolt"></i></div>
        <h3 class="font-semibold text-lg mb-2">API</h3>
        <p class="text-sm text-slate-400 leading-relaxed mb-4">
          Programmatically manage domains, DNS, listings, and site deployments. Perfect for agencies
          managing multiple client sites.
        </p>
        <a href="/api" class="text-sm text-blue-400 hover:text-blue-300 font-medium">API reference →</a>
      </article>
      <article class="card rounded-2xl p-6">
        <div class="text-pink-400 text-xl mb-3"><i class="fas fa-book"></i></div>
        <h3 class="font-semibold text-lg mb-2">Docs</h3>
        <p class="text-sm text-slate-400 leading-relaxed mb-4">
          Clear documentation for DNS, email workers, SEO best practices, and integrating third-party
          platforms with your site.
        </p>
        <a href="/docs" class="text-sm text-blue-400 hover:text-blue-300 font-medium">Read docs →</a>
      </article>
    </div>
  </section>

  <!-- ========== EXTRA VALUE (LA/OC + ownership) ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 pb-16">
    <div class="grid md:grid-cols-2 gap-5">
      <div class="card rounded-2xl p-6 md:p-8">
        <div class="text-emerald-400 mb-3"><i class="fas fa-map-marker-alt"></i></div>
        <h3 class="section-title text-xl font-bold mb-2">In-person in LA &amp; OC</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Prefer face-to-face? We offer service calls across Los Angeles and Orange County —
          discovery meetings, design reviews, staff training, and on-site help. Remote clients
          are fully supported online.
        </p>
      </div>
      <div class="card rounded-2xl p-6 md:p-8">
        <div class="text-blue-400 mb-3"><i class="fas fa-key"></i></div>
        <h3 class="section-title text-xl font-bold mb-2">You own the code &amp; data</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Built in-house. Source, assets, and deploy config are yours — not locked inside a page builder
          you rent forever. You dream. We code.
        </p>
      </div>
    </div>
  </section>

  <!-- ========== FINAL CTA ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 pb-20">
    <div class="card rounded-3xl p-8 md:p-12 text-center relative overflow-hidden">
      <div class="absolute inset-0 bg-gradient-to-br from-blue-600/10 via-transparent to-violet-600/10 pointer-events-none"></div>
      <div class="relative">
        <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
          Ready to Claim Your Online Presence?
        </h2>
        <p class="text-slate-400 max-w-xl mx-auto mb-8 leading-relaxed">
          Stop losing customers to unclaimed listings. Let’s build the website that ties everything
          together and gets you found.
        </p>
        <div class="flex flex-col sm:flex-row items-center justify-center gap-3 sm:gap-4">
          <a href="/contact" class="cta-primary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl">
            Contact Us Today
          </a>
          <a href="/tools/Domain_Search" class="cta-secondary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl">
            Search a Domain
          </a>
        </div>
      </div>
    </div>
  </section>

<div class="announcement-banner">
  <div class="banner-container">
    <div class="banner-text" id="bannerText"></div>
  </div>
</div>

<style>
.announcement-banner {
  width: 100%;
  height: 45px;
  background: linear-gradient(135deg, #0a0a0f, #0a0a0f);
  color: white;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 24px;
  font-weight: bold;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  position: relative;
  box-shadow: 0 2px 8px rgba(0,0,0,0.2);
  margin: 10px auto;
  border-radius: 4px;
}

.banner-container {
  width: 100%;
  height: 100%;
  position: relative;
}

.banner-text {
  position: absolute;
  width: 100%;
  text-align: center;
  padding: 0 20px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;

  /* Initial state */
  opacity: 0;
  transform: translateX(50px); /* Start slightly to the right */
  transition: all 0.7s cubic-bezier(0.4, 0, 0.2, 1);
}

/* Active state - visible and centered */
.banner-text.active {
  opacity: 1;
  transform: translateX(0);
}

/* Previous slide (for outgoing) */
.banner-text.out {
  opacity: 0;
  transform: translateX(-50px);
}
</style>

<script>
// Messages - edit these freely
const messages = [
  "🤖 Cloudflare AI",
  "GitHub for Version Control",
  "Google Business Claimed & Linked",
  "Facebook Optimization",
  "Rank #1 on Google",
  "Fine Tuned SEO Strategies",
  "Search Engine Optimized",
  "Analytics Engines",
  "Email Tracking Pixels",
  "Click Tracking",
  "Generate Email Templates",
  "Generate Keywords",
  "Generate Meta Tags",
  "Custom Smart AI Bots",
  "Email Automation",
  "Send Custom Emails",
  "Advanced Dashboards",
  "American Made Technology",
  "24/7 Live Developer Support",
  "You own the Source Code",
  "Custom Builds shipped World Wide"
];

let currentIndex = 0;
const bannerText = document.getElementById('bannerText');

function showMessage(index) {
  bannerText.innerHTML = messages[index];
  bannerText.classList.add('active');
}

function nextMessage() {
  const currentText = bannerText;

  // Start outgoing animation
  currentText.classList.add('out');

  setTimeout(() => {
    currentText.classList.remove('active', 'out');

    // Move to next message
    currentIndex = (currentIndex + 1) % messages.length;
    showMessage(currentIndex);
  }, 700); // Match transition duration
}

// Initialize first message
showMessage(0);

// Auto-rotate every 4.2 seconds
setInterval(nextMessage, 4200);
</script>
  <!-- Domain result modal -->
  <div id="domain-modal" class="domain-modal-backdrop" role="dialog" aria-modal="true" aria-labelledby="domain-modal-title" hidden>
    <div class="domain-modal">
      <div class="flex items-start justify-between gap-3 mb-4">
        <div class="flex items-center gap-3">
          <div id="domain-modal-icon" class="w-11 h-11 rounded-xl flex items-center justify-center text-lg bg-emerald-500/15 text-emerald-400">
            <i class="fas fa-check-circle"></i>
          </div>
          <h2 id="domain-modal-title" class="section-title text-xl font-bold">Domain Available!</h2>
        </div>
        <button type="button" id="domain-modal-close" class="text-slate-500 hover:text-white w-9 h-9 rounded-lg hover:bg-white/5" aria-label="Close">
          <i class="fas fa-times"></i>
        </button>
      </div>
      <p id="domain-modal-message" class="text-slate-300 text-sm leading-relaxed mb-6">
        Great news! <strong class="text-white" id="domain-modal-name">example.com</strong> is available for registration.
      </p>
      <div class="flex flex-col sm:flex-row gap-3">
        <a id="domain-modal-register" href="/register" class="cta-primary flex-1 text-center font-semibold py-3 rounded-xl text-sm">
          Register this domain
        </a>
        <button type="button" id="domain-modal-dismiss" class="cta-secondary flex-1 font-semibold py-3 rounded-xl text-sm">
          Search again
        </button>
      </div>
      <p class="text-xs text-slate-500 mt-4 text-center">
        Availability is checked via public DNS and is not a guarantee of registration success.
      </p>
    </div>
  </div>

  <!-- ========== FOOTER ========== -->
  <footer class="border-t border-white/10 py-10">
    <!--=== visitor counter ===-->
      <div id="my-visitor-counter"></div>
<script
  src="https://visitor-counter.registermysite.com/widget.js"
  data-container="my-visitor-counter"
></script>
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="flex flex-col md:flex-row md:items-start justify-between gap-8 mb-8">
        <div>
          <div class="flex items-center gap-2 mb-3">
           <!-- <div class="w-8 h-8 rounded-lg bg-gradient-to-br from-blue-500 to-violet-600 flex items-center justify-center font-bold text-white text-sm">R</div>
            <span class="font-semibold">registermysite.com</span> -->
          </div>
          <p class="text-sm text-slate-500 max-w-xs">Web development for multi-platform business presence. Domains, design, SEO, and email.</br>
          Register your website to start linking your accounts and Rank higher in search results against your competitors. Claim, Link and Rank. </p>
        </div>
        <div class="grid grid-cols-2 sm:grid-cols-3 gap-8 text-sm">
          <div>
            <div class="text-slate-400 font-medium mb-3">Product</div>
            <ul class="space-y-2 text-slate-500">
              <li><a href="/services" class="hover:text-blue-400">Services</a></li>
              <li><a href="/pricing" class="hover:text-blue-400">Pricing</a></li>
              <li><a href="/tools" class="hover:text-blue-400">Tools</a></li>
              <li><a href="/templates" class="hover:text-blue-400">Templates</a></li>
            </ul>
          </div>
          <div>
            <div class="text-slate-400 font-medium mb-3">Company</div>
            <ul class="space-y-2 text-slate-500">
              <li><a href="/docs" class="hover:text-blue-400">Docs</a></li>
              <li><a href="/api" class="hover:text-blue-400">API</a></li>
              <li><a href="/contact" class="hover:text-blue-400">Contact</a></li>
              <li><a href="/login" class="hover:text-blue-400">Login</a></li>
              <li><a href="/sitemap.html" class="hover:text-blue-400">Site Map</a></li>
            </ul>
          </div>
          <div>
            <div class="text-slate-400 font-medium mb-3">Contact</div>
            <ul class="space-y-2 text-slate-500">
              <li><a href="tel:+15627514597" class="hover:text-blue-400">(562) 751-4597</a></li>
              <li><a href="/cdn-cgi/l/email-protection#2b42454d446b594e4c42585f4e59465258425f4e05484446" class="hover:text-blue-400"><span class="__cf_email__" data-cfemail="eb82858d84ab998e8c82989f8e99869298829f8ec5888486">[email&#160;protected]</span></a></li>
            </ul>
          <img src="https://uploads.registermysite.com/applist.webp" alt="Venmo, CashApp, Zelle, Paypal payment methods accepted" id="PaymentLogo" style="max-width: 100%; height: auto;">
          </div>
        </div>
      </div>
       <a href="https://x.com/diyregistry" class="logo-circle" title="X.com">
  <img src="https://uploads.registermysite.com/favicon-x.png" alt="X" />
</a>
<a href="https://youtube.com/@RegisterMySite" href="https://www.youtube.com/channel/UCwwGNwZJ5JizhMoFU_Z-WOw" class="logo-circle" title="YouTube">
  <img src="https://uploads.registermysite.com/favicon-youtube.png" alt="YT" />
</a>
<a href="https://yelp.com/RegisterMySite" class="logo-circle" title="yelp">
  <img src="https://uploads.registermysite.com/yelp-icon.png" alt="yelp" />
</a>
<a href="https://www.tiktok.com/@registermysite?_r=1&_t=ZP-98fvlLBUhji" class="logo-circle" title="TikTok">
  <img src="https://uploads.registermysite.com/favicon-tiktok.png" alt="TikTok" />
</a>
<a href="https://instagram.com/RegisterMySite" class="logo-circle" title="InstaGram">
  <img src="https://uploads.registermysite.com/favicon-instagram.png" alt="Instagram" />
</a>
<a href="https://github.com/RegisterMySite-com" class="logo-circle" title="GitHub">
  <img src="https://uploads.registermysite.com/github-icon.jpeg" alt="GitHub" />
</a>
<a href="https://google.registermysite.com/Google-Business-Profile" class="logo-circle" title="Google">
  <img src="https://uploads.registermysite.com/google-icon.jpeg" alt="Google" />
</a>
<a href="https://www.facebook.com/profile.php?id=61592420500053&mibextid=ZbWKwL" class="logo-circle" title="Facebook">
  <img src="https://uploads.registermysite.com/facebook-icon.png" alt="Facebook" />
</a>
                <!-- Logo -->
        <a href="/" class="flex items-center gap-3 shrink-0">
          <div class="flex items-center gap-3">
        <img src="https://uploads.registermysite.com/registermysite.jpg" alt="Logo" class="h-10 w-10 rounded-xl object-cover bg-white/20">

          <div class="leading-tight">
            <span class="text-lg font-bold tracking-tight">RegisterMySite</span><span class="text-blue-400">.com</span>
          </div>
        </a>
            </div>
    </div>
  </footer>
<script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script>
  window.RMS_CHAT = {
    url: "https://ai.registermysite.com",
    title: "RegisterMySite AI",
    position: "right",   // or "left"
    openOnLoad: true,
    buttonLabel: "Chat"
  };
</script>
<script src="https://registermysite.com/ai-chat-widget.js" defer></script>
  <script>
    /* —— Mobile nav —— */
    const menuBtn = document.getElementById('menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');
    const menuIcon = document.getElementById('menu-icon');
    const toolsToggle = document.getElementById('tools-toggle');
    const toolsSub = document.getElementById('tools-sub');
    const toolsChevron = document.getElementById('tools-chevron');

    menuBtn.addEventListener('click', () => {
      const open = mobileMenu.classList.toggle('open');
      menuBtn.setAttribute('aria-expanded', open ? 'true' : 'false');
      menuIcon.className = open ? 'fas fa-times text-lg' : 'fas fa-bars text-lg';
      if (!open) {
        toolsSub.classList.remove('open');
        toolsChevron.style.transform = '';
      }
    });

    toolsToggle.addEventListener('click', () => {
      const open = toolsSub.classList.toggle('open');
      toolsChevron.style.transform = open ? 'rotate(180deg)' : '';
    });

    /* —— Domain search (Google DNS-over-HTTPS, same idea as Domain_Search) —— */
    const form = document.getElementById('hero-domain-form');
    const input = document.getElementById('hero-domain-input');
    const btn = document.getElementById('hero-domain-btn');
    const hint = document.getElementById('hero-domain-hint');
    const modal = document.getElementById('domain-modal');
    const modalTitle = document.getElementById('domain-modal-title');
    const modalMessage = document.getElementById('domain-modal-message');
    const modalName = document.getElementById('domain-modal-name');
    const modalIcon = document.getElementById('domain-modal-icon');
    const modalRegister = document.getElementById('domain-modal-register');
    const modalClose = document.getElementById('domain-modal-close');
    const modalDismiss = document.getElementById('domain-modal-dismiss');

    function normalizeDomain(raw) {
      let d = (raw || '').trim().toLowerCase();
      d = d.replace(/^https?:\/\//, '').replace(/^www\./, '').split('/')[0].split('?')[0];
      return d;
    }

    function isValidDomain(d) {
      return /^[a-z0-9]([a-z0-9-]{0,61}[a-z0-9])?(\.[a-z0-9]([a-z0-9-]{0,61}[a-z0-9])?)+$/i.test(d);
    }

    /** NXDOMAIN / no answers ≈ available; answers present ≈ taken */
    async function checkViaGoogleDNS(domain) {
      const url = `https://dns.google/resolve?name=${encodeURIComponent(domain)}&type=A`;
      const res = await fetch(url, { headers: { Accept: 'application/dns-json' } });
      if (!res.ok) throw new Error('DNS lookup failed');
      const data = await res.json();
      // Status 3 = NXDOMAIN (available). Status 0 with Answer = registered.
      if (data.Status === 3) return { available: true };
      if (data.Status === 0 && data.Answer && data.Answer.length > 0) return { available: false };
      // No answer records often means not resolving (treat as likely available)
      if (data.Status === 0 && (!data.Answer || data.Answer.length === 0)) return { available: true };
      return { available: false };
    }

    function openModal({ available, domain }) {
      modal.hidden = false;
      requestAnimationFrame(() => modal.classList.add('open'));

      if (available) {
        modalTitle.textContent = 'Domain Available!';
        modalIcon.className = 'w-11 h-11 rounded-xl flex items-center justify-center text-lg bg-emerald-500/15 text-emerald-400';
        modalIcon.innerHTML = '<i class="fas fa-check-circle"></i>';
        modalMessage.innerHTML = `Great news! <strong class="text-white" id="domain-modal-name">${escapeHtml(domain)}</strong> is available for registration.`;
        modalRegister.href = `https://registermysite.com/register?domain=${encodeURIComponent(domain)}`;
        modalRegister.style.display = '';
        modalRegister.textContent = 'Register this domain';
      } else {
        modalTitle.textContent = 'Domain Taken';
        modalIcon.className = 'w-11 h-11 rounded-xl flex items-center justify-center text-lg bg-amber-500/15 text-amber-400';
        modalIcon.innerHTML = '<i class="fas fa-times-circle"></i>';
        modalMessage.innerHTML = `<strong class="text-white">${escapeHtml(domain)}</strong> appears to be registered. Try another name or check advanced tools for alternatives.`;
        modalRegister.href = `/tools/Domain_Search`;
        modalRegister.textContent = 'Try advanced search';
      }
    }

    function closeModal() {
      modal.classList.remove('open');
      setTimeout(() => { modal.hidden = true; }, 200);
    }

    function escapeHtml(s) {
      return String(s)
        .replace(/&/g, '&amp;')
        .replace(/</g, '&lt;')
        .replace(/>/g, '&gt;')
        .replace(/"/g, '&quot;');
    }

    form.addEventListener('submit', async (e) => {
      e.preventDefault();
      const domain = normalizeDomain(input.value);
      hint.textContent = '';

      if (!domain) {
        hint.textContent = 'Enter a domain name to search.';
        hint.className = 'text-sm text-amber-400 mb-6 min-h-[1.25rem]';
        return;
      }
      if (!isValidDomain(domain)) {
        hint.textContent = 'Enter a valid domain like example.com';
        hint.className = 'text-sm text-amber-400 mb-6 min-h-[1.25rem]';
        return;
      }

      btn.disabled = true;
      btn.innerHTML = '<i class="fas fa-spinner fa-spin mr-1.5"></i> Checking…';
      hint.textContent = `Checking ${domain}…`;
      hint.className = 'text-sm text-slate-400 mb-6 min-h-[1.25rem]';

      try {
        const result = await checkViaGoogleDNS(domain);
        hint.textContent = '';
        openModal({ available: result.available, domain });
      } catch (err) {
        console.error(err);
        hint.textContent = 'Lookup failed. Please try again or use Domain Search tools.';
        hint.className = 'text-sm text-red-400 mb-6 min-h-[1.25rem]';
      } finally {
        btn.disabled = false;
        btn.innerHTML = '<i class="fas fa-search mr-1.5"></i> Search';
      }
    });

    modalClose.addEventListener('click', closeModal);
    modalDismiss.addEventListener('click', () => {
      closeModal();
      input.focus();
    });
    modal.addEventListener('click', (e) => {
      if (e.target === modal) closeModal();
    });
    document.addEventListener('keydown', (e) => {
      if (e.key === 'Escape' && modal.classList.contains('open')) closeModal();
    });
  </script>
</body>
</html></doc><doc title="SEO Optimization" desc="Technical SEO, schema markup, local SEO, and more"><!DOCTYPE html>
<html lang="en">
<head>

  <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence</title>
    <meta name="description" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">
    <meta name="title" content="RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <!-- Preconnect to the domain-->
    <link rel="preconnect" href="https://visitor-counter.registermysite.com" crossorigin>
    <!-- Optional: Preload the script for even faster loading -->
    <link rel="preload" href="https://visitor-counter.registermysite.com/widget.js" as="script">
  <!-- Favicons and install icons -->
  <link rel="icon" href="/assets/icons/favicon.ico" sizes="any">
  <link rel="icon" type="image/png" sizes="16x16" href="/assets/icons/favicon-16x16.jpg">
  <link rel="icon" type="image/png" sizes="32x32" href="/assets/icons/favicon-32x32.jpg">
  <link rel="icon" type="image/png" sizes="48x48" href="/assets/icons/favicon-48x48.jpg">
  <link rel="icon" type="image/png" sizes="96x96" href="/assets/icons/favicon-96x96.jpg">
  <link rel="apple-touch-icon" sizes="180x180" href="/assets/icons/apple-touch-icon.jpg">
  <link rel="manifest" href="/assets/manifest.json">

  <!-- Open Graph / Facebook -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://registermysite.com">
  <meta property="og:title" content="RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence">
  <meta property="og:description" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">
  <meta property="og:image" content="https://registermysite.com/assets/og-card.jpg">
  <meta property="og:image:width" content="1200">
  <meta property="og:image:height" content="630">
  <meta property="og:image:alt" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">

  <!-- Twitter -->
  <meta property="twitter:card" content="summary_large_image">
  <meta property="twitter:url" content="https://registermysite.com">
  <meta property="twitter:title" content="RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence">
  <meta property="twitter:description" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">
  <meta property="twitter:image" content="https://registermysite.com/assets/og-card.jpg">

  <!-- Structured data -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "WebApplication",
    "name": "Register My Site",
    "url": "https://registermysite.com",
    "description": "RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.",
    "applicationCategory": "UtilitiesApplication",
    "operatingSystem": "Any (Windows, macOS, Android, iOS, Linux, ChromeOS)",
    "isAccessibleForFree": true,
    "offers": {
      "@type": "Offer",
      "price": "0",
      "priceCurrency": "USD"
    }
  }
  </script>

  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Space+Grotesk:wght@500;600;700&display=swap');

    body {
      font-family: 'Inter', system-ui, sans-serif;
      background: #0a0a0f;
      color: #e2e8f0;
    }

    .section-title {
      font-family: 'Space Grotesk', sans-serif;
    }

    .gradient-text {
      background: linear-gradient(135deg, #60a5fa, #a78bfa, #f472b6);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }

    .card {
      background: rgba(255, 255, 255, 0.03);
      border: 1px solid rgba(255, 255, 255, 0.08);
      transition: border-color 0.2s, background 0.2s;
    }

    .card:hover {
      border-color: rgba(96, 165, 250, 0.28);
      background: rgba(255, 255, 255, 0.045);
    }

    /* Hero background image + overlay */
    .hero {
            background: linear-gradient(rgba(0,123,255,0.88), rgba(0,80,200,0.88)), url('https://uploads.registermysite.com/registermysite.gif?auto=format&fit=crop&w=1920&q=80') center/cover no-repeat;
            color: white;
            text-align: center;
            padding: 160px 20px 120px;
            position: relative;
        }

    .cta-primary {
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: #fff;
      transition: background 0.25s ease, transform 0.2s ease, box-shadow 0.25s ease;
    }

    .cta-primary {
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: #fff;
      transition: background 0.25s ease, transform 0.2s ease, box-shadow 0.25s ease;
    }

    .cta-primary:hover {
      background: linear-gradient(135deg, #22d3ee, #a78bfa);
      transform: translateY(-2px);
      box-shadow: 0 12px 32px rgba(96, 165, 250, 0.35);
    }

    .cta-secondary {
      background: transparent;
      color: #e2e8f0;
      border: 1px solid rgba(255, 255, 255, 0.2);
      transition: background 0.25s ease, border-color 0.25s ease, color 0.25s ease, transform 0.2s ease;
    }

    .cta-secondary:hover {
      background: rgba(96, 165, 250, 0.15);
      border-color: #60a5fa;
      color: #93c5fd;
      transform: translateY(-2px);
    }

    /* Domain search bar */
    .domain-search-wrap {
      display: flex;
      flex-direction: column;
      gap: 0.75rem;
      width: 100%;
      max-width: 36rem;
    }

    @media (min-width: 640px) {
      .domain-search-wrap {
        flex-direction: row;
        align-items: stretch;
      }
    }

    .domain-search-input {
      flex: 1;
      background: rgba(0, 0, 0, 0.55);
      border: 1px solid rgba(255, 255, 255, 0.14);
      color: #e2e8f0;
      border-radius: 12px;
      padding: 0.9rem 1.1rem;
      font-size: 1rem;
      transition: border-color 0.2s, box-shadow 0.2s;
      min-width: 0;
    }

    .domain-search-input:focus {
      outline: none;
      border-color: #60a5fa;
      box-shadow: 0 0 0 3px rgba(96, 165, 250, 0.2);
    }

    .domain-search-input::placeholder {
      color: #64748b;
    }

    .domain-search-btn {
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: #fff;
      border: none;
      border-radius: 12px;
      padding: 0.9rem 1.4rem;
      font-weight: 600;
      font-size: 0.95rem;
      cursor: pointer;
      white-space: nowrap;
      transition: background 0.25s ease, transform 0.2s ease, box-shadow 0.25s ease;
    }

    .domain-search-btn:hover:not(:disabled) {
      background: linear-gradient(135deg, #22d3ee, #a78bfa);
      transform: translateY(-1px);
      box-shadow: 0 10px 28px rgba(96, 165, 250, 0.35);
    }

    .domain-search-btn:disabled {
      opacity: 0.65;
      cursor: wait;
    }

    /* Result modal */
    .domain-modal-backdrop {
      position: fixed;
      inset: 0;
      background: rgba(0, 0, 0, 0.7);
      backdrop-filter: blur(6px);
      z-index: 100;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 1.25rem;
      opacity: 0;
      visibility: hidden;
      transition: opacity 0.2s ease, visibility 0.2s ease;
    }

    .domain-modal-backdrop.open {
      opacity: 1;
      visibility: visible;
    }

    .domain-modal {
      background: #12121a;
      border: 1px solid rgba(255, 255, 255, 0.12);
      border-radius: 1.25rem;
      padding: 1.75rem 1.5rem;
      width: 100%;
      max-width: 26rem;
      box-shadow: 0 24px 64px rgba(0, 0, 0, 0.5);
      transform: translateY(12px);
      transition: transform 0.2s ease;
    }

    .domain-modal-backdrop.open .domain-modal {
      transform: translateY(0);
    }

    /* Mobile menu */
    .mobile-panel {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.35s ease;
    }

    .mobile-panel.open {
      max-height: 640px;
    }

    .mobile-sub {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.3s ease;
    }

    .mobile-sub.open {
      max-height: 280px;
    }

    .nav-link {
      transition: color 0.15s ease;
    }

    .nav-link:hover {
      color: #60a5fa;
    }

    .status-pill {
      display: inline-flex;
      align-items: center;
      gap: 0.35rem;
      font-size: 0.75rem;
      padding: 0.35rem 0.7rem;
      border-radius: 9999px;
      background: rgba(16, 185, 129, 0.12);
      border: 1px solid rgba(16, 185, 129, 0.25);
      color: #6ee7b7;
    }

    .step-num {
      width: 2.25rem;
      height: 2.25rem;
      border-radius: 9999px;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      font-weight: 700;
      font-size: 0.9rem;
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: white;
      flex-shrink: 0;
    }
    .logo-circle {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 36px;          /* tiny size */
  height: 36px;
  border-radius: 50%;   /* makes it a circle */
  overflow: hidden;     /* clips the image to the circle */
  background: white;    /* optional fallback */
  border: 2px solid rgba(255,255,255,0.3);
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}

.logo-circle img {
  width: 100%;
  height: 100%;
  object-fit: cover;    /* fills the circle nicely */
}

.logo-circle:hover {
  transform: scale(1.08);
  box-shadow: 0 0 0 3px rgba(79, 70, 229, 0.3);
}
  </style>
   <!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-GMLQJKKPPP"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-GMLQJKKPPP');
</script>
</head>
<body class="min-h-screen">

  <!-- ========== NAVIGATION ========== -->
  <header class="border-b border-white/10 sticky top-0 z-50 backdrop-blur-xl bg-black/70">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="flex items-center justify-between h-16">
        <!-- Logo -->
        <a href="/" class="flex items-center gap-3 shrink-0">
          <img src="https://uploads.registermysite.com/registermysite.gif" alt="Logo" class="h-10 w-10 rounded-xl object-cover bg-white/20">
        <div>
         <span class="text-2xl font-bold tracking-tight">RegisterMySite</span><span class="text-blue-400">.com</span>
          </div>
        </a>

        <!-- Desktop nav -->
        <nav class="hidden lg:flex items-center gap-7 text-sm font-medium">
          <a href="/services" class="nav-link text-slate-300">Services</a>
          <a href="/pricing" class="nav-link text-slate-300">Pricing</a>
          <div class="relative group">
            <button type="button" class="nav-link text-slate-300 inline-flex items-center gap-1.5">
              Tools <i class="fas fa-chevron-down text-[10px] opacity-70"></i>
            </button>
            <div class="invisible opacity-0 group-hover:visible group-hover:opacity-100 transition-all duration-200 absolute top-full left-0 pt-2 w-56">
              <div class="card rounded-xl py-2 shadow-xl shadow-black/40">
                <a href="/tools/Domain_Search" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">Domain Search</a>
                <a href="/tools/TLDsearch" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">TLD Search</a>
                <a href="/tools/QR_Code" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">QR Code</a>
                <a href="/tools/og-preview" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">OG Preview</a>
                <a href="https://meta-gen.registermysite.com" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">Meta Generator</a>
                <a href="https://email-gen.registermysite.com" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">Email Template Generator</a>
                <a href="https://ai.editor.registermysite.com" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">HTML Website Generator</a>
                <a href="/tools" class="block px-4 py-2.5 text-sm text-blue-400 hover:bg-white/5 border-t border-white/10 mt-1 pt-2.5">All tools →</a>
              </div>
            </div>
          </div>
          <a href="/Web_Design" class="nav-link text-slate-300">Web Design</a>
          <a href="/Business_Email.html" class="nav-link text-slate-300">Business Email</a>
          <a href="/docs" class="nav-link text-slate-300">Docs</a>
          <a href="/contact" class="nav-link text-slate-300">Contact</a>
          <a href="/login" class="cta-primary text-sm font-semibold px-4 py-2 rounded-lg">Login</a>
        </nav>

        <!-- Mobile hamburger -->
        <button type="button" id="menu-btn" class="lg:hidden w-10 h-10 flex items-center justify-center rounded-lg border border-white/10 text-slate-200 hover:border-blue-400/40" aria-label="Open menu" aria-expanded="false">
          <i class="fas fa-bars text-lg" id="menu-icon"></i>
        </button>
      </div>

      <!-- Mobile dropdown panel -->
      <div id="mobile-menu" class="mobile-panel lg:hidden border-t border-white/10">
        <nav class="py-3 flex flex-col text-sm font-medium">
          <a href="/services" class="px-2 py-3 text-slate-300 hover:text-blue-400">Services</a>
          <a href="/pricing" class="px-2 py-3 text-slate-300 hover:text-blue-400">Pricing</a>

          <!-- Expandable: Tools -->
          <button type="button" id="tools-toggle" class="px-2 py-3 text-left text-slate-300 hover:text-blue-400 flex items-center justify-between w-full">
            <span>Tools</span>
            <i class="fas fa-chevron-down text-xs transition-transform duration-200" id="tools-chevron"></i>
          </button>
          <div id="tools-sub" class="mobile-sub bg-black/30 rounded-xl mx-1 mb-1">
            <a href="/tools/Domain_Search" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">Domain Search</a>
            <a href="/tools/TLDsearch" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">TLD Search</a>
            <a href="/tools/QR_Code" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">QR Code Generator</a>
            <a href="/tools/og-image" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">OG Image Generator</a>
            <a href="/tools/og-preview" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">OG Preview</a>
            <a href="https://meta-gen.registermysite.com" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">Meta Title Generator</a>
            <a href="https://email-gen.registermysite.com" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">Email Template Generator</a>
            <a href="https://ai.editor.registermysite.com" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">HTML Website Generator</a>
            <a href="/tools" class="block px-4 py-2.5 text-blue-400 hover:text-blue-300">View all tools →</a>
          </div>

          <a href="/Web_Design" class="px-2 py-3 text-slate-300 hover:text-blue-400">Web Design</a>
          <a href="/SEO_Optimization" class="px-2 py-3 text-slate-300 hover:text-blue-400">SEO</a>
          <a href="/Business_Email" class="px-2 py-3 text-slate-300 hover:text-blue-400">Business Email</a>
          <a href="/docs" class="px-2 py-3 text-slate-300 hover:text-blue-400">Docs</a>
          <a href="/contact" class="px-2 py-3 text-slate-300 hover:text-blue-400">Contact</a>
          <a href="/login" class="mx-2 mt-2 mb-3 cta-primary text-center font-semibold py-3 rounded-xl">Login / Sign up</a>
        </nav>
      </div>
    </div>
  </header>

  <!-- ========== HERO ========== -->
  <section class="hero">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-24 w-full relative z-10">
      <p class="text-blue-400 text-sm font-semibold tracking-wide uppercase mb-4">Web development agency</p>
      <h1 class="section-title text-4xl sm:text-5xl md:text-6xl font-bold leading-tight mb-5 max-w-3xl">
        Your Business <span class="gradient-text">Online</span>
      </h1>
      <p class="text-slate-300 text-lg md:text-xl max-w-2xl leading-relaxed mb-8">
        Multi-platform presence that ties your website, Google Business, Yelp, and social profiles together —
        so customers find a professional brand, not scattered listings.
      </p>

      <form id="hero-domain-form" class="domain-search-wrap mb-4" autocomplete="off">
        <input
          type="text"
          id="hero-domain-input"
          class="domain-search-input"
          placeholder="Search a domain — e.g. example.com"
          spellcheck="false"
          autocapitalize="off"
          inputmode="url"
          aria-label="Domain name to search"
        />
        <button type="submit" id="hero-domain-btn" class="domain-search-btn">
          <i class="fas fa-search mr-1.5"></i> Search
        </button>
      </form>
      <p id="hero-domain-hint" class="text-sm text-slate-500 mb-6 min-h-[1.25rem]"></p>

      <div class="flex flex-col sm:flex-row gap-3 sm:gap-4 mb-10">
        <a href="/contact" class="cta-secondary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl text-base">
          <i class="fas fa-envelope"></i>
          Contact Us Today
        </a>
        <a href="/tools/Domain_Search" class="cta-secondary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl text-base text-sm">
          Advanced domain tools →
        </a>
      </div>

      <!-- Platform status pills -->
      <div class="flex flex-wrap gap-2">
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Yelp · Claimed &amp; Linked</span>
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Google Business · Claimed &amp; Linked</span>
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Facebook · Connected</span>
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Instagram · Connected</span>
      </div>
    </div>
  </section>

  <!-- ========== CORE SERVICES ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-20">
    <div class="text-center mb-12">
      <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
        Everything Your Business Needs <span class="gradient-text">Online</span>
      </h2>
      <p class="text-slate-400 text-base md:text-lg max-w-2xl mx-auto leading-relaxed">
        From domain setup to SEO-powered websites and professional email — we handle the technical side
        so you can focus on customers.
      </p>
    </div>

    <div class="grid sm:grid-cols-2 gap-5">
      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-blue-500/15 text-blue-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-globe"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">Domain &amp; DNS Setup</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          We register or connect your domain, configure DNS records correctly, and make sure everything
          points to your new site with zero downtime.
        </p>
      </article>

      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-violet-500/15 text-violet-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-magnifying-glass"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">SEO Optimization</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Technical SEO, schema markup, local SEO, and strategic linking of all your platform profiles
          so Google ranks your business higher.
        </p>
      </article>

      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-pink-500/15 text-pink-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-palette"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">Web Design &amp; Templates</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Beautiful, conversion-focused designs and ready-to-use industry templates. Fully responsive
          and mobile-first for every device.
        </p>
      </article>

      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-emerald-500/15 text-emerald-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-envelope"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">Custom Business Email</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Professional email addresses (@yourbusiness.com) with auto-reply workers that respond
          instantly while you’re busy with customers.
        </p>
      </article>
    </div>
  </section>

  <!-- ========== HOW IT WORKS ========== -->
  <section class="border-y border-white/5 bg-white/[0.015]">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-20">
      <div class="text-center mb-12">
        <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
          How It <span class="gradient-text">Works</span>
        </h2>
        <p class="text-slate-400 max-w-xl mx-auto">
          From scattered listings to a fully connected online presence in four simple steps.
        </p>
      </div>

      <div class="grid md:grid-cols-2 gap-5">
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">1</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Audit Your Listings</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              We find every unclaimed or disconnected profile for your business across major platforms.
            </p>
          </div>
        </div>
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">2</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Build Your Website</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              Choose a template or go custom. We create a site that showcases your business and services.
            </p>
          </div>
        </div>
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">3</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Claim &amp; Link Everything</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              We claim your Yelp, Google Business, and other accounts and link them back to your new website.
            </p>
          </div>
        </div>
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">4</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Launch &amp; Rank</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              DNS, SEO, emails, and analytics go live. Your business becomes discoverable and professional.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ========== TOOLS ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-20">
    <div class="text-center mb-12">
      <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
        Built for Developers &amp; <span class="gradient-text">Businesses</span>
      </h2>
      <p class="text-slate-400 max-w-xl mx-auto">
        Powerful tools when you need them, simple when you don’t.
      </p>
    </div>

    <div class="grid md:grid-cols-3 gap-5">
      <article class="card rounded-2xl p-6">
        <div class="text-blue-400 text-xl mb-3"><i class="fas fa-file-lines"></i></div>
        <h3 class="font-semibold text-lg mb-2">Templates</h3>
        <p class="text-sm text-slate-400 leading-relaxed mb-4">
          Browse dozens of industry-ready website templates. Restaurants, salons, contractors, clinics —
          pick one and customize in minutes.
        </p>
        <a href="/templates" class="text-sm text-blue-400 hover:text-blue-300 font-medium">Browse templates →</a>
      </article>
      <article class="card rounded-2xl p-6">
        <div class="text-violet-400 text-xl mb-3"><i class="fas fa-bolt"></i></div>
        <h3 class="font-semibold text-lg mb-2">API</h3>
        <p class="text-sm text-slate-400 leading-relaxed mb-4">
          Programmatically manage domains, DNS, listings, and site deployments. Perfect for agencies
          managing multiple client sites.
        </p>
        <a href="/api" class="text-sm text-blue-400 hover:text-blue-300 font-medium">API reference →</a>
      </article>
      <article class="card rounded-2xl p-6">
        <div class="text-pink-400 text-xl mb-3"><i class="fas fa-book"></i></div>
        <h3 class="font-semibold text-lg mb-2">Docs</h3>
        <p class="text-sm text-slate-400 leading-relaxed mb-4">
          Clear documentation for DNS, email workers, SEO best practices, and integrating third-party
          platforms with your site.
        </p>
        <a href="/docs" class="text-sm text-blue-400 hover:text-blue-300 font-medium">Read docs →</a>
      </article>
    </div>
  </section>

  <!-- ========== EXTRA VALUE (LA/OC + ownership) ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 pb-16">
    <div class="grid md:grid-cols-2 gap-5">
      <div class="card rounded-2xl p-6 md:p-8">
        <div class="text-emerald-400 mb-3"><i class="fas fa-map-marker-alt"></i></div>
        <h3 class="section-title text-xl font-bold mb-2">In-person in LA &amp; OC</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Prefer face-to-face? We offer service calls across Los Angeles and Orange County —
          discovery meetings, design reviews, staff training, and on-site help. Remote clients
          are fully supported online.
        </p>
      </div>
      <div class="card rounded-2xl p-6 md:p-8">
        <div class="text-blue-400 mb-3"><i class="fas fa-key"></i></div>
        <h3 class="section-title text-xl font-bold mb-2">You own the code &amp; data</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Built in-house. Source, assets, and deploy config are yours — not locked inside a page builder
          you rent forever. You dream. We code.
        </p>
      </div>
    </div>
  </section>

  <!-- ========== FINAL CTA ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 pb-20">
    <div class="card rounded-3xl p-8 md:p-12 text-center relative overflow-hidden">
      <div class="absolute inset-0 bg-gradient-to-br from-blue-600/10 via-transparent to-violet-600/10 pointer-events-none"></div>
      <div class="relative">
        <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
          Ready to Claim Your Online Presence?
        </h2>
        <p class="text-slate-400 max-w-xl mx-auto mb-8 leading-relaxed">
          Stop losing customers to unclaimed listings. Let’s build the website that ties everything
          together and gets you found.
        </p>
        <div class="flex flex-col sm:flex-row items-center justify-center gap-3 sm:gap-4">
          <a href="/contact" class="cta-primary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl">
            Contact Us Today
          </a>
          <a href="/tools/Domain_Search" class="cta-secondary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl">
            Search a Domain
          </a>
        </div>
      </div>
    </div>
  </section>

<div class="announcement-banner">
  <div class="banner-container">
    <div class="banner-text" id="bannerText"></div>
  </div>
</div>

<style>
.announcement-banner {
  width: 100%;
  height: 45px;
  background: linear-gradient(135deg, #0a0a0f, #0a0a0f);
  color: white;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 24px;
  font-weight: bold;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  position: relative;
  box-shadow: 0 2px 8px rgba(0,0,0,0.2);
  margin: 10px auto;
  border-radius: 4px;
}

.banner-container {
  width: 100%;
  height: 100%;
  position: relative;
}

.banner-text {
  position: absolute;
  width: 100%;
  text-align: center;
  padding: 0 20px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;

  /* Initial state */
  opacity: 0;
  transform: translateX(50px); /* Start slightly to the right */
  transition: all 0.7s cubic-bezier(0.4, 0, 0.2, 1);
}

/* Active state - visible and centered */
.banner-text.active {
  opacity: 1;
  transform: translateX(0);
}

/* Previous slide (for outgoing) */
.banner-text.out {
  opacity: 0;
  transform: translateX(-50px);
}
</style>

<script>
// Messages - edit these freely
const messages = [
  "🤖 Cloudflare AI",
  "GitHub for Version Control",
  "Google Business Claimed & Linked",
  "Facebook Optimization",
  "Rank #1 on Google",
  "Fine Tuned SEO Strategies",
  "Search Engine Optimized",
  "Analytics Engines",
  "Email Tracking Pixels",
  "Click Tracking",
  "Generate Email Templates",
  "Generate Keywords",
  "Generate Meta Tags",
  "Custom Smart AI Bots",
  "Email Automation",
  "Send Custom Emails",
  "Advanced Dashboards",
  "American Made Technology",
  "24/7 Live Developer Support",
  "You own the Source Code",
  "Custom Builds shipped World Wide"
];

let currentIndex = 0;
const bannerText = document.getElementById('bannerText');

function showMessage(index) {
  bannerText.innerHTML = messages[index];
  bannerText.classList.add('active');
}

function nextMessage() {
  const currentText = bannerText;

  // Start outgoing animation
  currentText.classList.add('out');

  setTimeout(() => {
    currentText.classList.remove('active', 'out');

    // Move to next message
    currentIndex = (currentIndex + 1) % messages.length;
    showMessage(currentIndex);
  }, 700); // Match transition duration
}

// Initialize first message
showMessage(0);

// Auto-rotate every 4.2 seconds
setInterval(nextMessage, 4200);
</script>
  <!-- Domain result modal -->
  <div id="domain-modal" class="domain-modal-backdrop" role="dialog" aria-modal="true" aria-labelledby="domain-modal-title" hidden>
    <div class="domain-modal">
      <div class="flex items-start justify-between gap-3 mb-4">
        <div class="flex items-center gap-3">
          <div id="domain-modal-icon" class="w-11 h-11 rounded-xl flex items-center justify-center text-lg bg-emerald-500/15 text-emerald-400">
            <i class="fas fa-check-circle"></i>
          </div>
          <h2 id="domain-modal-title" class="section-title text-xl font-bold">Domain Available!</h2>
        </div>
        <button type="button" id="domain-modal-close" class="text-slate-500 hover:text-white w-9 h-9 rounded-lg hover:bg-white/5" aria-label="Close">
          <i class="fas fa-times"></i>
        </button>
      </div>
      <p id="domain-modal-message" class="text-slate-300 text-sm leading-relaxed mb-6">
        Great news! <strong class="text-white" id="domain-modal-name">example.com</strong> is available for registration.
      </p>
      <div class="flex flex-col sm:flex-row gap-3">
        <a id="domain-modal-register" href="/register" class="cta-primary flex-1 text-center font-semibold py-3 rounded-xl text-sm">
          Register this domain
        </a>
        <button type="button" id="domain-modal-dismiss" class="cta-secondary flex-1 font-semibold py-3 rounded-xl text-sm">
          Search again
        </button>
      </div>
      <p class="text-xs text-slate-500 mt-4 text-center">
        Availability is checked via public DNS and is not a guarantee of registration success.
      </p>
    </div>
  </div>

  <!-- ========== FOOTER ========== -->
  <footer class="border-t border-white/10 py-10">
    <!--=== visitor counter ===-->
      <div id="my-visitor-counter"></div>
<script
  src="https://visitor-counter.registermysite.com/widget.js"
  data-container="my-visitor-counter"
></script>
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="flex flex-col md:flex-row md:items-start justify-between gap-8 mb-8">
        <div>
          <div class="flex items-center gap-2 mb-3">
           <!-- <div class="w-8 h-8 rounded-lg bg-gradient-to-br from-blue-500 to-violet-600 flex items-center justify-center font-bold text-white text-sm">R</div>
            <span class="font-semibold">registermysite.com</span> -->
          </div>
          <p class="text-sm text-slate-500 max-w-xs">Web development for multi-platform business presence. Domains, design, SEO, and email.</br>
          Register your website to start linking your accounts and Rank higher in search results against your competitors. Claim, Link and Rank. </p>
        </div>
        <div class="grid grid-cols-2 sm:grid-cols-3 gap-8 text-sm">
          <div>
            <div class="text-slate-400 font-medium mb-3">Product</div>
            <ul class="space-y-2 text-slate-500">
              <li><a href="/services" class="hover:text-blue-400">Services</a></li>
              <li><a href="/pricing" class="hover:text-blue-400">Pricing</a></li>
              <li><a href="/tools" class="hover:text-blue-400">Tools</a></li>
              <li><a href="/templates" class="hover:text-blue-400">Templates</a></li>
            </ul>
          </div>
          <div>
            <div class="text-slate-400 font-medium mb-3">Company</div>
            <ul class="space-y-2 text-slate-500">
              <li><a href="/docs" class="hover:text-blue-400">Docs</a></li>
              <li><a href="/api" class="hover:text-blue-400">API</a></li>
              <li><a href="/contact" class="hover:text-blue-400">Contact</a></li>
              <li><a href="/login" class="hover:text-blue-400">Login</a></li>
              <li><a href="/sitemap.html" class="hover:text-blue-400">Site Map</a></li>
            </ul>
          </div>
          <div>
            <div class="text-slate-400 font-medium mb-3">Contact</div>
            <ul class="space-y-2 text-slate-500">
              <li><a href="tel:+15627514597" class="hover:text-blue-400">(562) 751-4597</a></li>
              <li><a href="/cdn-cgi/l/email-protection#462f282029063423212f353223342b3f352f32236825292b" class="hover:text-blue-400"><span class="__cf_email__" data-cfemail="7f161119103f0d1a18160c0b1a0d12060c160b1a511c1012">[email&#160;protected]</span></a></li>
            </ul>
          <img src="https://uploads.registermysite.com/applist.webp" alt="Venmo, CashApp, Zelle, Paypal payment methods accepted" id="PaymentLogo" style="max-width: 100%; height: auto;">
          </div>
        </div>
      </div>
       <a href="https://x.com/diyregistry" class="logo-circle" title="X.com">
  <img src="https://uploads.registermysite.com/favicon-x.png" alt="X" />
</a>
<a href="https://youtube.com/@RegisterMySite" href="https://www.youtube.com/channel/UCwwGNwZJ5JizhMoFU_Z-WOw" class="logo-circle" title="YouTube">
  <img src="https://uploads.registermysite.com/favicon-youtube.png" alt="YT" />
</a>
<a href="https://yelp.com/RegisterMySite" class="logo-circle" title="yelp">
  <img src="https://uploads.registermysite.com/yelp-icon.png" alt="yelp" />
</a>
<a href="https://www.tiktok.com/@registermysite?_r=1&_t=ZP-98fvlLBUhji" class="logo-circle" title="TikTok">
  <img src="https://uploads.registermysite.com/favicon-tiktok.png" alt="TikTok" />
</a>
<a href="https://instagram.com/RegisterMySite" class="logo-circle" title="InstaGram">
  <img src="https://uploads.registermysite.com/favicon-instagram.png" alt="Instagram" />
</a>
<a href="https://github.com/RegisterMySite-com" class="logo-circle" title="GitHub">
  <img src="https://uploads.registermysite.com/github-icon.jpeg" alt="GitHub" />
</a>
<a href="https://google.registermysite.com/Google-Business-Profile" class="logo-circle" title="Google">
  <img src="https://uploads.registermysite.com/google-icon.jpeg" alt="Google" />
</a>
<a href="https://www.facebook.com/profile.php?id=61592420500053&mibextid=ZbWKwL" class="logo-circle" title="Facebook">
  <img src="https://uploads.registermysite.com/facebook-icon.png" alt="Facebook" />
</a>
                <!-- Logo -->
        <a href="/" class="flex items-center gap-3 shrink-0">
          <div class="flex items-center gap-3">
        <img src="https://uploads.registermysite.com/registermysite.jpg" alt="Logo" class="h-10 w-10 rounded-xl object-cover bg-white/20">

          <div class="leading-tight">
            <span class="text-lg font-bold tracking-tight">RegisterMySite</span><span class="text-blue-400">.com</span>
          </div>
        </a>
            </div>
    </div>
  </footer>
<script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script>
  window.RMS_CHAT = {
    url: "https://ai.registermysite.com",
    title: "RegisterMySite AI",
    position: "right",   // or "left"
    openOnLoad: true,
    buttonLabel: "Chat"
  };
</script>
<script src="https://registermysite.com/ai-chat-widget.js" defer></script>
  <script>
    /* —— Mobile nav —— */
    const menuBtn = document.getElementById('menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');
    const menuIcon = document.getElementById('menu-icon');
    const toolsToggle = document.getElementById('tools-toggle');
    const toolsSub = document.getElementById('tools-sub');
    const toolsChevron = document.getElementById('tools-chevron');

    menuBtn.addEventListener('click', () => {
      const open = mobileMenu.classList.toggle('open');
      menuBtn.setAttribute('aria-expanded', open ? 'true' : 'false');
      menuIcon.className = open ? 'fas fa-times text-lg' : 'fas fa-bars text-lg';
      if (!open) {
        toolsSub.classList.remove('open');
        toolsChevron.style.transform = '';
      }
    });

    toolsToggle.addEventListener('click', () => {
      const open = toolsSub.classList.toggle('open');
      toolsChevron.style.transform = open ? 'rotate(180deg)' : '';
    });

    /* —— Domain search (Google DNS-over-HTTPS, same idea as Domain_Search) —— */
    const form = document.getElementById('hero-domain-form');
    const input = document.getElementById('hero-domain-input');
    const btn = document.getElementById('hero-domain-btn');
    const hint = document.getElementById('hero-domain-hint');
    const modal = document.getElementById('domain-modal');
    const modalTitle = document.getElementById('domain-modal-title');
    const modalMessage = document.getElementById('domain-modal-message');
    const modalName = document.getElementById('domain-modal-name');
    const modalIcon = document.getElementById('domain-modal-icon');
    const modalRegister = document.getElementById('domain-modal-register');
    const modalClose = document.getElementById('domain-modal-close');
    const modalDismiss = document.getElementById('domain-modal-dismiss');

    function normalizeDomain(raw) {
      let d = (raw || '').trim().toLowerCase();
      d = d.replace(/^https?:\/\//, '').replace(/^www\./, '').split('/')[0].split('?')[0];
      return d;
    }

    function isValidDomain(d) {
      return /^[a-z0-9]([a-z0-9-]{0,61}[a-z0-9])?(\.[a-z0-9]([a-z0-9-]{0,61}[a-z0-9])?)+$/i.test(d);
    }

    /** NXDOMAIN / no answers ≈ available; answers present ≈ taken */
    async function checkViaGoogleDNS(domain) {
      const url = `https://dns.google/resolve?name=${encodeURIComponent(domain)}&type=A`;
      const res = await fetch(url, { headers: { Accept: 'application/dns-json' } });
      if (!res.ok) throw new Error('DNS lookup failed');
      const data = await res.json();
      // Status 3 = NXDOMAIN (available). Status 0 with Answer = registered.
      if (data.Status === 3) return { available: true };
      if (data.Status === 0 && data.Answer && data.Answer.length > 0) return { available: false };
      // No answer records often means not resolving (treat as likely available)
      if (data.Status === 0 && (!data.Answer || data.Answer.length === 0)) return { available: true };
      return { available: false };
    }

    function openModal({ available, domain }) {
      modal.hidden = false;
      requestAnimationFrame(() => modal.classList.add('open'));

      if (available) {
        modalTitle.textContent = 'Domain Available!';
        modalIcon.className = 'w-11 h-11 rounded-xl flex items-center justify-center text-lg bg-emerald-500/15 text-emerald-400';
        modalIcon.innerHTML = '<i class="fas fa-check-circle"></i>';
        modalMessage.innerHTML = `Great news! <strong class="text-white" id="domain-modal-name">${escapeHtml(domain)}</strong> is available for registration.`;
        modalRegister.href = `https://registermysite.com/register?domain=${encodeURIComponent(domain)}`;
        modalRegister.style.display = '';
        modalRegister.textContent = 'Register this domain';
      } else {
        modalTitle.textContent = 'Domain Taken';
        modalIcon.className = 'w-11 h-11 rounded-xl flex items-center justify-center text-lg bg-amber-500/15 text-amber-400';
        modalIcon.innerHTML = '<i class="fas fa-times-circle"></i>';
        modalMessage.innerHTML = `<strong class="text-white">${escapeHtml(domain)}</strong> appears to be registered. Try another name or check advanced tools for alternatives.`;
        modalRegister.href = `/tools/Domain_Search`;
        modalRegister.textContent = 'Try advanced search';
      }
    }

    function closeModal() {
      modal.classList.remove('open');
      setTimeout(() => { modal.hidden = true; }, 200);
    }

    function escapeHtml(s) {
      return String(s)
        .replace(/&/g, '&amp;')
        .replace(/</g, '&lt;')
        .replace(/>/g, '&gt;')
        .replace(/"/g, '&quot;');
    }

    form.addEventListener('submit', async (e) => {
      e.preventDefault();
      const domain = normalizeDomain(input.value);
      hint.textContent = '';

      if (!domain) {
        hint.textContent = 'Enter a domain name to search.';
        hint.className = 'text-sm text-amber-400 mb-6 min-h-[1.25rem]';
        return;
      }
      if (!isValidDomain(domain)) {
        hint.textContent = 'Enter a valid domain like example.com';
        hint.className = 'text-sm text-amber-400 mb-6 min-h-[1.25rem]';
        return;
      }

      btn.disabled = true;
      btn.innerHTML = '<i class="fas fa-spinner fa-spin mr-1.5"></i> Checking…';
      hint.textContent = `Checking ${domain}…`;
      hint.className = 'text-sm text-slate-400 mb-6 min-h-[1.25rem]';

      try {
        const result = await checkViaGoogleDNS(domain);
        hint.textContent = '';
        openModal({ available: result.available, domain });
      } catch (err) {
        console.error(err);
        hint.textContent = 'Lookup failed. Please try again or use Domain Search tools.';
        hint.className = 'text-sm text-red-400 mb-6 min-h-[1.25rem]';
      } finally {
        btn.disabled = false;
        btn.innerHTML = '<i class="fas fa-search mr-1.5"></i> Search';
      }
    });

    modalClose.addEventListener('click', closeModal);
    modalDismiss.addEventListener('click', () => {
      closeModal();
      input.focus();
    });
    modal.addEventListener('click', (e) => {
      if (e.target === modal) closeModal();
    });
    document.addEventListener('keydown', (e) => {
      if (e.key === 'Escape' && modal.classList.contains('open')) closeModal();
    });
  </script>
</body>
</html></doc><doc title="Web Design &amp; Templates" desc="Responsive, mobile-first, conversion-focused designs"><!DOCTYPE html>
<html lang="en">
<head>
   <!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-GMLQJKKPPP"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-GMLQJKKPPP');
</script>
   <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Templates & Tools — registermysite.com</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Space+Grotesk:wght@500;600;700&display=swap');
        body { font-family: 'Inter', system-ui, sans-serif; background: #0a0a0f; color: #e2e8f0; }
        .gradient-text { background: linear-gradient(135deg, #60a5fa, #a78bfa, #f472b6); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
        .card { background: rgba(255,255,255,0.03); border: 1px solid rgba(255,255,255,0.08); transition: all 0.3s ease; }
        .card:hover { border-color: rgba(96,165,250,0.4); transform: translateY(-4px); box-shadow: 0 20px 40px rgba(0,0,0,0.4); }
        .section-title { font-family: 'Space Grotesk', sans-serif; }
        .popular { border: 2px solid #60a5fa; position: relative; }
        .popular::before {
            content: "MOST POPULAR";
            position: absolute;
            top: -12px;
            left: 50%;
            transform: translateX(-50%);
            background: linear-gradient(90deg, #3b82f6, #8b5cf6);
            color: white;
            font-size: 11px;
            font-weight: 700;
            padding: 4px 14px;
            border-radius: 999px;
            letter-spacing: 0.5px;
        }
    </style>
</head>
<body class="min-h-screen">

    <!-- Header -->
    <header class="border-b border-white/10 sticky top-0 z-50 backdrop-blur-xl bg-black/60">
        <div class="max-w-7xl mx-auto px-6 py-5 flex items-center justify-between">
            <div class="flex items-center gap-3">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-br from-blue-500 to-violet-600 flex items-center justify-center font-bold text-white text-lg">R</div>
                <div>
                    <span class="text-xl font-bold tracking-tight">registermysite</span><span class="text-blue-400">.com</span>
                </div>
            </div>
            <nav class="hidden md:flex items-center gap-8 text-sm font-medium">
                <a href="/templates.html" class="hover:text-blue-400 transition">Templates</a>
                <a href="/tools.html" class="hover:text-blue-400 transition">QR Tools</a>
                <a href="/dashboard.html" class="hover:text-blue-400 transition">Dashboard</a>
                <a href="/addons.html" class="hover:text-blue-400 transition">Add-ons</a>
                <a href="/pricing.html" class="hover:text-blue-400 transition">Pricing</a>
                </nav>
            <a href="#contact" class="bg-blue-600 hover:bg-blue-500 transition px-6 py-2.5 rounded-full text-sm font-semibold">Get Started</a>
        </div>

        </header>

    <!-- Hero -->
    <section class="relative overflow-hidden">
        <div class="absolute inset-0 bg-gradient-to-b from-blue-900/20 via-transparent to-transparent"></div>
        <div class="max-w-7xl mx-auto px-6 pt-24 pb-20 text-center relative">
            <p class="text-blue-400 font-semibold tracking-widest uppercase text-sm mb-4">Website Templates • Tools • Analytics</p>
            <h1 class="section-title text-5xl md:text-7xl font-bold leading-tight mb-6">
                You Dream.<br>
                <span class="gradient-text">We Code.</span>
            </h1>
            <p class="text-xl text-slate-400 max-w-2xl mx-auto mb-10">
                Professional website templates, powerful QR generators, and a private analytics dashboard — all under one roof at registermysite.com.
            </p>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="#templates" class="bg-blue-600 hover:bg-blue-500 px-8 py-4 rounded-2xl font-semibold transition">Browse Templates</a>
                <a href="#pricing" class="border border-white/20 hover:border-blue-400 px-8 py-4 rounded-2xl font-semibold transition">View Pricing</a>
            </div>
        </div>
    </section>

    <!-- Templates Section -->
    <section id="templates" class="max-w-7xl mx-auto px-6 py-24">
        <div class="text-center mb-16">
            <h2 class="section-title text-4xl font-bold mb-4">Website Templates</h2>
            <p class="text-slate-400 max-w-2xl mx-auto">Ready-to-launch designs for every business type. Fully customizable, mobile-first, and SEO-optimized.</p>
        </div>

        <div class="grid md:grid-cols-2 gap-8">
            <!-- eCommerce -->
            <div class="card rounded-3xl p-10">
                <div class="flex items-center gap-3 mb-6">
                    <div class="w-12 h-12 rounded-2xl bg-blue-500/20 flex items-center justify-center text-blue-400 text-xl">
                        <i class="fas fa-shopping-cart"></i>
                    </div>
                    <div>
                        <h3 class="text-2xl font-bold">eCommerce Templates</h3>
                        <p class="text-sm text-slate-400">Sell products online with confidence</p>
                    </div>
                </div>
                <p class="text-slate-300 mb-6 leading-relaxed">
                    High-converting storefronts built for modern online retail. Product grids, cart & checkout flows, inventory management, and payment integrations.
                </p>
                <div class="bg-black/40 rounded-2xl p-6 border border-white/5 mb-6">
                    <p class="text-xs uppercase tracking-widest text-blue-400 mb-2">Live Example</p>
                    <a href="https://shastastash.com" target="_blank" class="text-lg font-semibold hover:text-blue-400 transition flex items-center gap-2">
                        shastastash.com <i class="fas fa-external-link-alt text-sm"></i>
                    </a>
                    <p class="text-sm text-slate-400 mt-2">A fully functional eCommerce experience powered by our template system.</p>
                </div>
                <ul class="space-y-3 text-sm text-slate-300">
                    <li class="flex items-center gap-2"><i class="fas fa-check text-blue-400"></i> Product catalogs & variants</li>
                    <li class="flex items-center gap-2"><i class="fas fa-check text-blue-400"></i> Stripe / PayPal / Crypto payments</li>
                    <li class="flex items-center gap-2"><i class="fas fa-check text-blue-400"></i> Inventory tracking & order management</li>
                    <li class="flex items-center gap-2"><i class="fas fa-check text-blue-400"></i> Mobile-optimized checkout</li>
                </ul>
            </div>

            <!-- Service Based -->
            <div class="card rounded-3xl p-10">
                <div class="flex items-center gap-3 mb-6">
                    <div class="w-12 h-12 rounded-2xl bg-violet-500/20 flex items-center justify-center text-violet-400 text-xl">
                        <i class="fas fa-tools"></i>
                    </div>
                    <div>
                        <h3 class="text-2xl font-bold">Service-Based Templates</h3>
                        <p class="text-sm text-slate-400">Book clients & showcase your work</p>
                    </div>
                </div>
                <p class="text-slate-300 mb-6 leading-relaxed">
                    Perfect for local businesses, contractors, detailers, salons, and professional services. Booking systems, galleries, testimonials, and contact funnels.
                </p>
                <div class="bg-black/40 rounded-2xl p-6 border border-white/5 mb-6">
                    <p class="text-xs uppercase tracking-widest text-violet-400 mb-2">Live Example</p>
                    <a href="https://automarinedetailers.com" target="_blank" class="text-lg font-semibold hover:text-violet-400 transition flex items-center gap-2">
                        automarinedetailers.com <i class="fas fa-external-link-alt text-sm"></i>
                    </a>
                    <p class="text-sm text-slate-400 mt-2">A polished service business site with booking-ready design.</p>
                </div>
                <ul class="space-y-3 text-sm text-slate-300">
                    <li class="flex items-center gap-2"><i class="fas fa-check text-violet-400"></i> Online booking & calendars</li>
                    <li class="flex items-center gap-2"><i class="fas fa-check text-violet-400"></i> Before/After galleries</li>
                    <li class="flex items-center gap-2"><i class="fas fa-check text-violet-400"></i> Service packages & pricing</li>
                    <li class="flex items-center gap-2"><i class="fas fa-check text-violet-400"></i> Lead capture forms</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- QR Tools Section -->
    <section id="tools" class="bg-gradient-to-b from-transparent via-blue-950/20 to-transparent py-24">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="section-title text-4xl font-bold mb-4">QR Code & Barcode Tools</h2>
                <p class="text-slate-400 max-w-2xl mx-auto">Generate professional QR codes and barcodes instantly — no account required for basic use.</p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
                <div class="card rounded-2xl p-8 text-center">
                    <div class="w-14 h-14 mx-auto rounded-2xl bg-green-500/20 flex items-center justify-center text-green-400 text-2xl mb-5">
                        <i class="fas fa-dollar-sign"></i>
                    </div>
                    <h3 class="font-bold text-lg mb-2">Cash App Pay QR</h3>
                    <p class="text-sm text-slate-400">Create branded Cash App payment QR codes for instant mobile payments.</p>
                </div>

                <div class="card rounded-2xl p-8 text-center">
                    <div class="w-14 h-14 mx-auto rounded-2xl bg-amber-500/20 flex items-center justify-center text-amber-400 text-2xl mb-5">
                        <i class="fab fa-bitcoin"></i>
                    </div>
                    <h3 class="font-bold text-lg mb-2">Bitcoin Pay QR</h3>
                    <p class="text-sm text-slate-400">BIP21-compliant Bitcoin payment QR codes with amount & message support.</p>
                </div>

                <div class="card rounded-2xl p-8 text-center">
                    <div class="w-14 h-14 mx-auto rounded-2xl bg-blue-500/20 flex items-center justify-center text-blue-400 text-2xl mb-5">
                        <i class="fas fa-qrcode"></i>
                    </div>
                    <h3 class="font-bold text-lg mb-2">Base64 QR + Scanner</h3>
                    <p class="text-sm text-slate-400">Encode any text into Base64 QR codes with built-in scanner & decoder.</p>
                </div>

                <div class="card rounded-2xl p-8 text-center">
                    <div class="w-14 h-14 mx-auto rounded-2xl bg-pink-500/20 flex items-center justify-center text-pink-400 text-2xl mb-5">
                        <i class="fas fa-barcode"></i>
                    </div>
                    <h3 class="font-bold text-lg mb-2">PDF417 Barcodes</h3>
                    <p class="text-sm text-slate-400">High-capacity PDF417 barcodes ideal for inventory tracking & shipping labels.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Dashboard Section -->
    <section id="dashboard" class="max-w-7xl mx-auto px-6 py-24">
        <div class="grid lg:grid-cols-2 gap-16 items-center">
            <div>
                <p class="text-blue-400 font-semibold tracking-widest uppercase text-sm mb-3">Private Customer Dashboard</p>
                <h2 class="section-title text-4xl font-bold mb-6">Link Shortener + Rich Analytics</h2>
                <p class="text-slate-300 text-lg leading-relaxed mb-8">
                    Every customer receives a secure personal login to their private dashboard. Create short links that generate QR codes packed with rich analytics captured on every scan.
                </p>
                <ul class="space-y-4 mb-10">
                    <li class="flex items-start gap-3">
                        <i class="fas fa-chart-line text-blue-400 mt-1"></i>
                        <div>
                            <strong>Total Scans</strong>
                            <p class="text-sm text-slate-400">Real-time count of every QR scan worldwide.</p>
                        </div>
                    </li>
                    <li class="flex items-start gap-3">
                        <i class="fas fa-clock text-blue-400 mt-1"></i>
                        <div>
                            <strong>Timestamp</strong>
                            <p class="text-sm text-slate-400">Exact date & time of each scan.</p>
                        </div>
                    </li>
                    <li class="flex items-start gap-3">
                        <i class="fas fa-globe text-blue-400 mt-1"></i>
                        <div>
                            <strong>IP Address</strong>
                            <p class="text-sm text-slate-400">Geographic & network origin of the visitor.</p>
                        </div>
                    </li>
                    <li class="flex items-start gap-3">
                        <i class="fas fa-mobile-alt text-blue-400 mt-1"></i>
                        <div>
                            <strong>User Agent</strong>
                            <p class="text-sm text-slate-400">Device, browser, and OS information.</p>
                        </div>
                    </li>
                    <li class="flex items-start gap-3">
                        <i class="fas fa-link text-blue-400 mt-1"></i>
                        <div>
                            <strong>Referrer</strong>
                            <p class="text-sm text-slate-400">Where the visitor came from before scanning.</p>
                        </div>
                    </li>
                </ul>
                <a href="#contact" class="inline-flex items-center gap-2 bg-blue-600 hover:bg-blue-500 px-8 py-4 rounded-2xl font-semibold transition">
                    Request Dashboard Access <i class="fas fa-arrow-right"></i>
                </a>
            </div>
            <div class="card rounded-3xl p-8">
                <div class="bg-black/50 rounded-2xl p-6 border border-white/10">
                    <div class="flex items-center justify-between mb-6">
                        <span class="text-sm font-mono text-slate-400">dashboard.registermysite.com</span>
                        <span class="text-xs bg-green-500/20 text-green-400 px-3 py-1 rounded-full">LIVE</span>
                    </div>
                    <div class="space-y-4 font-mono text-sm">
                        <div class="flex justify-between border-b border-white/5 pb-3">
                            <span class="text-slate-400">Total Scans</span>
                            <span class="text-blue-400 font-bold">12,847</span>
                        </div>
                        <div class="flex justify-between border-b border-white/5 pb-3">
                            <span class="text-slate-400">Last Scan</span>
                            <span>2026-07-24 21:47:12</span>
                        </div>
                        <div class="flex justify-between border-b border-white/5 pb-3">
                            <span class="text-slate-400">IP</span>
                            <span>104.28.***.***</span>
                        </div>
                        <div class="flex justify-between border-b border-white/5 pb-3">
                            <span class="text-slate-400">User Agent</span>
                            <span class="truncate max-w-[180px]">iPhone / Safari</span>
                        </div>
                        <div class="flex justify-between">
                            <span class="text-slate-400">Referrer</span>
                            <span class="text-violet-400">instagram.com</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Add-ons -->
    <section id="addons" class="max-w-7xl mx-auto px-6 py-24">
        <div class="text-center mb-16">
            <h2 class="section-title text-4xl font-bold mb-4">Powerful Add-ons</h2>
            <p class="text-slate-400 max-w-2xl mx-auto">Extend any template with ready-made modules. If you can dream it, we can achieve it.</p>
        </div>

        <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-6">
            <div class="card rounded-2xl p-8">
                <i class="fas fa-users text-3xl text-blue-400 mb-4"></i>
                <h3 class="font-bold text-xl mb-2">Visitor Counters</h3>
                <p class="text-sm text-slate-400">Live or historical visitor counters with location heatmaps and peak-hour insights.</p>
            </div>
            <div class="card rounded-2xl p-8">
                <i class="fas fa-comments text-3xl text-violet-400 mb-4"></i>
                <h3 class="font-bold text-xl mb-2">AI Chatbots</h3>
                <p class="text-sm text-slate-400">Smart chat widgets that answer FAQs, capture leads, and book appointments 24/7.</p>
            </div>
            <div class="card rounded-2xl p-8">
                <i class="fas fa-share-alt text-3xl text-pink-400 mb-4"></i>
                <h3 class="font-bold text-xl mb-2">Social Media Carousels</h3>
                <p class="text-sm text-slate-400">Auto-updating Instagram, TikTok, and Facebook feeds that keep your site fresh.</p>
            </div>
            <div class="card rounded-2xl p-8">
                <i class="fas fa-star text-3xl text-amber-400 mb-4"></i>
                <h3 class="font-bold text-xl mb-2">Review Carousels</h3>
                <p class="text-sm text-slate-400">Pull Google, Yelp, and Facebook reviews into beautiful rotating testimonials.</p>
            </div>
            <div class="card rounded-2xl p-8">
                <i class="fas fa-calendar-check text-3xl text-emerald-400 mb-4"></i>
                <h3 class="font-bold text-xl mb-2">Booking Systems</h3>
                <p class="text-sm text-slate-400">Full calendar integration with SMS/email reminders and deposit collection.</p>
            </div>
            <div class="card rounded-2xl p-8">
                <i class="fas fa-magic text-3xl text-cyan-400 mb-4"></i>
                <h3 class="font-bold text-xl mb-2">Custom Everything</h3>
                <p class="text-sm text-slate-400">You dream it — we code it. Custom features, integrations, and workflows on demand.</p>
            </div>
        </div>
    </section>

    <!-- Pricing Tiers -->
    <section id="pricing" class="bg-gradient-to-b from-transparent via-violet-950/20 to-transparent py-24">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="section-title text-4xl font-bold mb-4">Add-on Pricing Tiers</h2>
                <p class="text-slate-400 max-w-2xl mx-auto">Simple, transparent pricing. Choose the package that fits your business needs. All plans include setup & support.</p>
            </div>

            <div class="grid md:grid-cols-3 gap-8 max-w-6xl mx-auto">

                <!-- Starter -->
                <div class="card rounded-3xl p-10 flex flex-col">
                    <div class="mb-6">
                        <p class="text-sm uppercase tracking-widest text-slate-400 mb-2">Starter</p>
                        <h3 class="text-3xl font-bold mb-1">$49<span class="text-lg text-slate-400 font-normal">/mo</span></h3>
                        <p class="text-sm text-slate-400">Perfect for getting started</p>
                    </div>
                    <ul class="space-y-4 text-sm flex-1 mb-8">
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> Visitor Counter</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> Social Media Carousel (1 feed)</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> Basic Link Shortener</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> QR Code Generator Access</li>
                        <li class="flex items-center gap-3 text-slate-500"><i class="fas fa-times"></i> AI Chatbot</li>
                        <li class="flex items-center gap-3 text-slate-500"><i class="fas fa-times"></i> Review Carousel</li>
                        <li class="flex items-center gap-3 text-slate-500"><i class="fas fa-times"></i> Booking System</li>
                        <li class="flex items-center gap-3 text-slate-500"><i class="fas fa-times"></i> Rich Analytics Dashboard</li>
                    </ul>
                    <a href="#contact" class="block text-center border border-white/20 hover:border-blue-400 py-4 rounded-2xl font-semibold transition">Choose Starter</a>
                </div>

                <!-- Growth (Popular) -->
                <div class="card popular rounded-3xl p-10 flex flex-col bg-blue-950/30">
                    <div class="mb-6">
                        <p class="text-sm uppercase tracking-widest text-blue-400 mb-2">Growth</p>
                        <h3 class="text-3xl font-bold mb-1">$129<span class="text-lg text-slate-400 font-normal">/mo</span></h3>
                        <p class="text-sm text-slate-400">Most popular for growing businesses</p>
                    </div>
                    <ul class="space-y-4 text-sm flex-1 mb-8">
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> Everything in Starter</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> AI Chatbot (up to 500 chats/mo)</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> Review Carousel (Google + Yelp)</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> Social Media Carousels (3 feeds)</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> Rich Analytics Dashboard</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> Link Shortener + QR Analytics</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-blue-400"></i> Priority Email Support</li>
                        <li class="flex items-center gap-3 text-slate-500"><i class="fas fa-times"></i> Full Booking System</li>
                    </ul>
                    <a href="#contact" class="block text-center bg-blue-600 hover:bg-blue-500 py-4 rounded-2xl font-semibold transition">Choose Growth</a>
                </div>

                <!-- Pro -->
                <div class="card rounded-3xl p-10 flex flex-col">
                    <div class="mb-6">
                        <p class="text-sm uppercase tracking-widest text-violet-400 mb-2">Pro</p>
                        <h3 class="text-3xl font-bold mb-1">$299<span class="text-lg text-slate-400 font-normal">/mo</span></h3>
                        <p class="text-sm text-slate-400">Full power + custom development</p>
                    </div>
                    <ul class="space-y-4 text-sm flex-1 mb-8">
                        <li class="flex items-center gap-3"><i class="fas fa-check text-violet-400"></i> Everything in Growth</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-violet-400"></i> Unlimited AI Chatbot</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-violet-400"></i> Full Booking System + SMS</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-violet-400"></i> Unlimited Social Feeds</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-violet-400"></i> Advanced Analytics + Export</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-violet-400"></i> Custom Feature Development</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-violet-400"></i> Dedicated Support Channel</li>
                        <li class="flex items-center gap-3"><i class="fas fa-check text-violet-400"></i> White-label Options</li>
                    </ul>
                    <a href="#contact" class="block text-center border border-violet-500/50 hover:bg-violet-600/20 py-4 rounded-2xl font-semibold transition">Choose Pro</a>
                </div>
            </div>

            <p class="text-center text-sm text-slate-500 mt-12">
                All plans billed monthly. Annual billing available with 2 months free. Custom enterprise packages available upon request.
            </p>
        </div>
    </section>

    <!-- CTA -->
    <section id="contact" class="max-w-4xl mx-auto px-6 py-24 text-center">
        <div class="card rounded-3xl p-12 md:p-16">
            <h2 class="section-title text-4xl md:text-5xl font-bold mb-6">
                You Dream.<br>
                <span class="gradient-text">We Code.</span>
            </h2>
            <p class="text-slate-400 text-lg mb-10 max-w-xl mx-auto">
                Ready to launch your site, generate smart QR codes, or unlock your private analytics dashboard? Let’s build something great together.
            </p>
            <a href="/cdn-cgi/l/email-protection#563e333a3a39162433313f252233243b2f253f22337835393b" class="inline-flex items-center gap-3 bg-gradient-to-r from-blue-600 to-violet-600 hover:from-blue-500 hover:to-violet-500 px-10 py-5 rounded-2xl font-bold text-lg transition">
                <i class="fas fa-paper-plane"></i>
                Start Your Project
            </a>
        </div>
    </section>

    <!-- Footer -->
    <footer class="border-t border-white/10 py-12">
        <div class="max-w-7xl mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-6 text-sm text-slate-500">
            <div class="flex items-center gap-2">
                <div class="w-8 h-8 rounded-lg bg-gradient-to-br from-blue-500 to-violet-600 flex items-center justify-center font-bold text-white text-sm">R</div>
                <span>registermysite.com</span>
            </div>
            <p>© 2026 registermysite.com — Templates, Tools & Analytics</p>
            <p class="italic">If you can dream it, we can achieve it.</p>
        </div>
    </footer>

<script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script></body>
</html></doc><doc title="Custom Business Email" desc="Professional @yourbusiness.com addresses"><!DOCTYPE html>
<html lang="en">
<head>

  <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence</title>
    <meta name="description" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">
    <meta name="title" content="RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <!-- Preconnect to the domain-->
    <link rel="preconnect" href="https://visitor-counter.registermysite.com" crossorigin>
    <!-- Optional: Preload the script for even faster loading -->
    <link rel="preload" href="https://visitor-counter.registermysite.com/widget.js" as="script">
  <!-- Favicons and install icons -->
  <link rel="icon" href="/assets/icons/favicon.ico" sizes="any">
  <link rel="icon" type="image/png" sizes="16x16" href="/assets/icons/favicon-16x16.jpg">
  <link rel="icon" type="image/png" sizes="32x32" href="/assets/icons/favicon-32x32.jpg">
  <link rel="icon" type="image/png" sizes="48x48" href="/assets/icons/favicon-48x48.jpg">
  <link rel="icon" type="image/png" sizes="96x96" href="/assets/icons/favicon-96x96.jpg">
  <link rel="apple-touch-icon" sizes="180x180" href="/assets/icons/apple-touch-icon.jpg">
  <link rel="manifest" href="/assets/manifest.json">

  <!-- Open Graph / Facebook -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://registermysite.com">
  <meta property="og:title" content="RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence">
  <meta property="og:description" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">
  <meta property="og:image" content="https://registermysite.com/assets/og-card.jpg">
  <meta property="og:image:width" content="1200">
  <meta property="og:image:height" content="630">
  <meta property="og:image:alt" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">

  <!-- Twitter -->
  <meta property="twitter:card" content="summary_large_image">
  <meta property="twitter:url" content="https://registermysite.com">
  <meta property="twitter:title" content="RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence">
  <meta property="twitter:description" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">
  <meta property="twitter:image" content="https://registermysite.com/assets/og-card.jpg">

  <!-- Structured data -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "WebApplication",
    "name": "Register My Site",
    "url": "https://registermysite.com",
    "description": "RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.",
    "applicationCategory": "UtilitiesApplication",
    "operatingSystem": "Any (Windows, macOS, Android, iOS, Linux, ChromeOS)",
    "isAccessibleForFree": true,
    "offers": {
      "@type": "Offer",
      "price": "0",
      "priceCurrency": "USD"
    }
  }
  </script>

  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Space+Grotesk:wght@500;600;700&display=swap');

    body {
      font-family: 'Inter', system-ui, sans-serif;
      background: #0a0a0f;
      color: #e2e8f0;
    }

    .section-title {
      font-family: 'Space Grotesk', sans-serif;
    }

    .gradient-text {
      background: linear-gradient(135deg, #60a5fa, #a78bfa, #f472b6);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }

    .card {
      background: rgba(255, 255, 255, 0.03);
      border: 1px solid rgba(255, 255, 255, 0.08);
      transition: border-color 0.2s, background 0.2s;
    }

    .card:hover {
      border-color: rgba(96, 165, 250, 0.28);
      background: rgba(255, 255, 255, 0.045);
    }

    /* Hero background image + overlay */
    .hero {
            background: linear-gradient(rgba(0,123,255,0.88), rgba(0,80,200,0.88)), url('https://uploads.registermysite.com/registermysite.gif?auto=format&fit=crop&w=1920&q=80') center/cover no-repeat;
            color: white;
            text-align: center;
            padding: 160px 20px 120px;
            position: relative;
        }

    .cta-primary {
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: #fff;
      transition: background 0.25s ease, transform 0.2s ease, box-shadow 0.25s ease;
    }

    .cta-primary {
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: #fff;
      transition: background 0.25s ease, transform 0.2s ease, box-shadow 0.25s ease;
    }

    .cta-primary:hover {
      background: linear-gradient(135deg, #22d3ee, #a78bfa);
      transform: translateY(-2px);
      box-shadow: 0 12px 32px rgba(96, 165, 250, 0.35);
    }

    .cta-secondary {
      background: transparent;
      color: #e2e8f0;
      border: 1px solid rgba(255, 255, 255, 0.2);
      transition: background 0.25s ease, border-color 0.25s ease, color 0.25s ease, transform 0.2s ease;
    }

    .cta-secondary:hover {
      background: rgba(96, 165, 250, 0.15);
      border-color: #60a5fa;
      color: #93c5fd;
      transform: translateY(-2px);
    }

    /* Domain search bar */
    .domain-search-wrap {
      display: flex;
      flex-direction: column;
      gap: 0.75rem;
      width: 100%;
      max-width: 36rem;
    }

    @media (min-width: 640px) {
      .domain-search-wrap {
        flex-direction: row;
        align-items: stretch;
      }
    }

    .domain-search-input {
      flex: 1;
      background: rgba(0, 0, 0, 0.55);
      border: 1px solid rgba(255, 255, 255, 0.14);
      color: #e2e8f0;
      border-radius: 12px;
      padding: 0.9rem 1.1rem;
      font-size: 1rem;
      transition: border-color 0.2s, box-shadow 0.2s;
      min-width: 0;
    }

    .domain-search-input:focus {
      outline: none;
      border-color: #60a5fa;
      box-shadow: 0 0 0 3px rgba(96, 165, 250, 0.2);
    }

    .domain-search-input::placeholder {
      color: #64748b;
    }

    .domain-search-btn {
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: #fff;
      border: none;
      border-radius: 12px;
      padding: 0.9rem 1.4rem;
      font-weight: 600;
      font-size: 0.95rem;
      cursor: pointer;
      white-space: nowrap;
      transition: background 0.25s ease, transform 0.2s ease, box-shadow 0.25s ease;
    }

    .domain-search-btn:hover:not(:disabled) {
      background: linear-gradient(135deg, #22d3ee, #a78bfa);
      transform: translateY(-1px);
      box-shadow: 0 10px 28px rgba(96, 165, 250, 0.35);
    }

    .domain-search-btn:disabled {
      opacity: 0.65;
      cursor: wait;
    }

    /* Result modal */
    .domain-modal-backdrop {
      position: fixed;
      inset: 0;
      background: rgba(0, 0, 0, 0.7);
      backdrop-filter: blur(6px);
      z-index: 100;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 1.25rem;
      opacity: 0;
      visibility: hidden;
      transition: opacity 0.2s ease, visibility 0.2s ease;
    }

    .domain-modal-backdrop.open {
      opacity: 1;
      visibility: visible;
    }

    .domain-modal {
      background: #12121a;
      border: 1px solid rgba(255, 255, 255, 0.12);
      border-radius: 1.25rem;
      padding: 1.75rem 1.5rem;
      width: 100%;
      max-width: 26rem;
      box-shadow: 0 24px 64px rgba(0, 0, 0, 0.5);
      transform: translateY(12px);
      transition: transform 0.2s ease;
    }

    .domain-modal-backdrop.open .domain-modal {
      transform: translateY(0);
    }

    /* Mobile menu */
    .mobile-panel {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.35s ease;
    }

    .mobile-panel.open {
      max-height: 640px;
    }

    .mobile-sub {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.3s ease;
    }

    .mobile-sub.open {
      max-height: 280px;
    }

    .nav-link {
      transition: color 0.15s ease;
    }

    .nav-link:hover {
      color: #60a5fa;
    }

    .status-pill {
      display: inline-flex;
      align-items: center;
      gap: 0.35rem;
      font-size: 0.75rem;
      padding: 0.35rem 0.7rem;
      border-radius: 9999px;
      background: rgba(16, 185, 129, 0.12);
      border: 1px solid rgba(16, 185, 129, 0.25);
      color: #6ee7b7;
    }

    .step-num {
      width: 2.25rem;
      height: 2.25rem;
      border-radius: 9999px;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      font-weight: 700;
      font-size: 0.9rem;
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: white;
      flex-shrink: 0;
    }
    .logo-circle {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 36px;          /* tiny size */
  height: 36px;
  border-radius: 50%;   /* makes it a circle */
  overflow: hidden;     /* clips the image to the circle */
  background: white;    /* optional fallback */
  border: 2px solid rgba(255,255,255,0.3);
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}

.logo-circle img {
  width: 100%;
  height: 100%;
  object-fit: cover;    /* fills the circle nicely */
}

.logo-circle:hover {
  transform: scale(1.08);
  box-shadow: 0 0 0 3px rgba(79, 70, 229, 0.3);
}
  </style>
   <!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-GMLQJKKPPP"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-GMLQJKKPPP');
</script>
</head>
<body class="min-h-screen">

  <!-- ========== NAVIGATION ========== -->
  <header class="border-b border-white/10 sticky top-0 z-50 backdrop-blur-xl bg-black/70">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="flex items-center justify-between h-16">
        <!-- Logo -->
        <a href="/" class="flex items-center gap-3 shrink-0">
          <img src="https://uploads.registermysite.com/registermysite.gif" alt="Logo" class="h-10 w-10 rounded-xl object-cover bg-white/20">
        <div>
         <span class="text-2xl font-bold tracking-tight">RegisterMySite</span><span class="text-blue-400">.com</span>
          </div>
        </a>

        <!-- Desktop nav -->
        <nav class="hidden lg:flex items-center gap-7 text-sm font-medium">
          <a href="/services" class="nav-link text-slate-300">Services</a>
          <a href="/pricing" class="nav-link text-slate-300">Pricing</a>
          <div class="relative group">
            <button type="button" class="nav-link text-slate-300 inline-flex items-center gap-1.5">
              Tools <i class="fas fa-chevron-down text-[10px] opacity-70"></i>
            </button>
            <div class="invisible opacity-0 group-hover:visible group-hover:opacity-100 transition-all duration-200 absolute top-full left-0 pt-2 w-56">
              <div class="card rounded-xl py-2 shadow-xl shadow-black/40">
                <a href="/tools/Domain_Search" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">Domain Search</a>
                <a href="/tools/TLDsearch" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">TLD Search</a>
                <a href="/tools/QR_Code" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">QR Code</a>
                <a href="/tools/og-preview" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">OG Preview</a>
                <a href="https://meta-gen.registermysite.com" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">Meta Generator</a>
                <a href="https://email-gen.registermysite.com" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">Email Template Generator</a>
                <a href="https://ai.editor.registermysite.com" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">HTML Website Generator</a>
                <a href="/tools" class="block px-4 py-2.5 text-sm text-blue-400 hover:bg-white/5 border-t border-white/10 mt-1 pt-2.5">All tools →</a>
              </div>
            </div>
          </div>
          <a href="/Web_Design" class="nav-link text-slate-300">Web Design</a>
          <a href="/Business_Email.html" class="nav-link text-slate-300">Business Email</a>
          <a href="/docs" class="nav-link text-slate-300">Docs</a>
          <a href="/contact" class="nav-link text-slate-300">Contact</a>
          <a href="/login" class="cta-primary text-sm font-semibold px-4 py-2 rounded-lg">Login</a>
        </nav>

        <!-- Mobile hamburger -->
        <button type="button" id="menu-btn" class="lg:hidden w-10 h-10 flex items-center justify-center rounded-lg border border-white/10 text-slate-200 hover:border-blue-400/40" aria-label="Open menu" aria-expanded="false">
          <i class="fas fa-bars text-lg" id="menu-icon"></i>
        </button>
      </div>

      <!-- Mobile dropdown panel -->
      <div id="mobile-menu" class="mobile-panel lg:hidden border-t border-white/10">
        <nav class="py-3 flex flex-col text-sm font-medium">
          <a href="/services" class="px-2 py-3 text-slate-300 hover:text-blue-400">Services</a>
          <a href="/pricing" class="px-2 py-3 text-slate-300 hover:text-blue-400">Pricing</a>

          <!-- Expandable: Tools -->
          <button type="button" id="tools-toggle" class="px-2 py-3 text-left text-slate-300 hover:text-blue-400 flex items-center justify-between w-full">
            <span>Tools</span>
            <i class="fas fa-chevron-down text-xs transition-transform duration-200" id="tools-chevron"></i>
          </button>
          <div id="tools-sub" class="mobile-sub bg-black/30 rounded-xl mx-1 mb-1">
            <a href="/tools/Domain_Search" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">Domain Search</a>
            <a href="/tools/TLDsearch" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">TLD Search</a>
            <a href="/tools/QR_Code" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">QR Code Generator</a>
            <a href="/tools/og-image" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">OG Image Generator</a>
            <a href="/tools/og-preview" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">OG Preview</a>
            <a href="https://meta-gen.registermysite.com" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">Meta Title Generator</a>
            <a href="https://email-gen.registermysite.com" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">Email Template Generator</a>
            <a href="https://ai.editor.registermysite.com" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">HTML Website Generator</a>
            <a href="/tools" class="block px-4 py-2.5 text-blue-400 hover:text-blue-300">View all tools →</a>
          </div>

          <a href="/Web_Design" class="px-2 py-3 text-slate-300 hover:text-blue-400">Web Design</a>
          <a href="/SEO_Optimization" class="px-2 py-3 text-slate-300 hover:text-blue-400">SEO</a>
          <a href="/Business_Email" class="px-2 py-3 text-slate-300 hover:text-blue-400">Business Email</a>
          <a href="/docs" class="px-2 py-3 text-slate-300 hover:text-blue-400">Docs</a>
          <a href="/contact" class="px-2 py-3 text-slate-300 hover:text-blue-400">Contact</a>
          <a href="/login" class="mx-2 mt-2 mb-3 cta-primary text-center font-semibold py-3 rounded-xl">Login / Sign up</a>
        </nav>
      </div>
    </div>
  </header>

  <!-- ========== HERO ========== -->
  <section class="hero">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-24 w-full relative z-10">
      <p class="text-blue-400 text-sm font-semibold tracking-wide uppercase mb-4">Web development agency</p>
      <h1 class="section-title text-4xl sm:text-5xl md:text-6xl font-bold leading-tight mb-5 max-w-3xl">
        Your Business <span class="gradient-text">Online</span>
      </h1>
      <p class="text-slate-300 text-lg md:text-xl max-w-2xl leading-relaxed mb-8">
        Multi-platform presence that ties your website, Google Business, Yelp, and social profiles together —
        so customers find a professional brand, not scattered listings.
      </p>

      <form id="hero-domain-form" class="domain-search-wrap mb-4" autocomplete="off">
        <input
          type="text"
          id="hero-domain-input"
          class="domain-search-input"
          placeholder="Search a domain — e.g. example.com"
          spellcheck="false"
          autocapitalize="off"
          inputmode="url"
          aria-label="Domain name to search"
        />
        <button type="submit" id="hero-domain-btn" class="domain-search-btn">
          <i class="fas fa-search mr-1.5"></i> Search
        </button>
      </form>
      <p id="hero-domain-hint" class="text-sm text-slate-500 mb-6 min-h-[1.25rem]"></p>

      <div class="flex flex-col sm:flex-row gap-3 sm:gap-4 mb-10">
        <a href="/contact" class="cta-secondary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl text-base">
          <i class="fas fa-envelope"></i>
          Contact Us Today
        </a>
        <a href="/tools/Domain_Search" class="cta-secondary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl text-base text-sm">
          Advanced domain tools →
        </a>
      </div>

      <!-- Platform status pills -->
      <div class="flex flex-wrap gap-2">
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Yelp · Claimed &amp; Linked</span>
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Google Business · Claimed &amp; Linked</span>
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Facebook · Connected</span>
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Instagram · Connected</span>
      </div>
    </div>
  </section>

  <!-- ========== CORE SERVICES ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-20">
    <div class="text-center mb-12">
      <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
        Everything Your Business Needs <span class="gradient-text">Online</span>
      </h2>
      <p class="text-slate-400 text-base md:text-lg max-w-2xl mx-auto leading-relaxed">
        From domain setup to SEO-powered websites and professional email — we handle the technical side
        so you can focus on customers.
      </p>
    </div>

    <div class="grid sm:grid-cols-2 gap-5">
      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-blue-500/15 text-blue-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-globe"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">Domain &amp; DNS Setup</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          We register or connect your domain, configure DNS records correctly, and make sure everything
          points to your new site with zero downtime.
        </p>
      </article>

      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-violet-500/15 text-violet-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-magnifying-glass"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">SEO Optimization</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Technical SEO, schema markup, local SEO, and strategic linking of all your platform profiles
          so Google ranks your business higher.
        </p>
      </article>

      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-pink-500/15 text-pink-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-palette"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">Web Design &amp; Templates</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Beautiful, conversion-focused designs and ready-to-use industry templates. Fully responsive
          and mobile-first for every device.
        </p>
      </article>

      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-emerald-500/15 text-emerald-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-envelope"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">Custom Business Email</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Professional email addresses (@yourbusiness.com) with auto-reply workers that respond
          instantly while you’re busy with customers.
        </p>
      </article>
    </div>
  </section>

  <!-- ========== HOW IT WORKS ========== -->
  <section class="border-y border-white/5 bg-white/[0.015]">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-20">
      <div class="text-center mb-12">
        <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
          How It <span class="gradient-text">Works</span>
        </h2>
        <p class="text-slate-400 max-w-xl mx-auto">
          From scattered listings to a fully connected online presence in four simple steps.
        </p>
      </div>

      <div class="grid md:grid-cols-2 gap-5">
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">1</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Audit Your Listings</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              We find every unclaimed or disconnected profile for your business across major platforms.
            </p>
          </div>
        </div>
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">2</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Build Your Website</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              Choose a template or go custom. We create a site that showcases your business and services.
            </p>
          </div>
        </div>
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">3</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Claim &amp; Link Everything</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              We claim your Yelp, Google Business, and other accounts and link them back to your new website.
            </p>
          </div>
        </div>
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">4</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Launch &amp; Rank</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              DNS, SEO, emails, and analytics go live. Your business becomes discoverable and professional.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ========== TOOLS ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-20">
    <div class="text-center mb-12">
      <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
        Built for Developers &amp; <span class="gradient-text">Businesses</span>
      </h2>
      <p class="text-slate-400 max-w-xl mx-auto">
        Powerful tools when you need them, simple when you don’t.
      </p>
    </div>

    <div class="grid md:grid-cols-3 gap-5">
      <article class="card rounded-2xl p-6">
        <div class="text-blue-400 text-xl mb-3"><i class="fas fa-file-lines"></i></div>
        <h3 class="font-semibold text-lg mb-2">Templates</h3>
        <p class="text-sm text-slate-400 leading-relaxed mb-4">
          Browse dozens of industry-ready website templates. Restaurants, salons, contractors, clinics —
          pick one and customize in minutes.
        </p>
        <a href="/templates" class="text-sm text-blue-400 hover:text-blue-300 font-medium">Browse templates →</a>
      </article>
      <article class="card rounded-2xl p-6">
        <div class="text-violet-400 text-xl mb-3"><i class="fas fa-bolt"></i></div>
        <h3 class="font-semibold text-lg mb-2">API</h3>
        <p class="text-sm text-slate-400 leading-relaxed mb-4">
          Programmatically manage domains, DNS, listings, and site deployments. Perfect for agencies
          managing multiple client sites.
        </p>
        <a href="/api" class="text-sm text-blue-400 hover:text-blue-300 font-medium">API reference →</a>
      </article>
      <article class="card rounded-2xl p-6">
        <div class="text-pink-400 text-xl mb-3"><i class="fas fa-book"></i></div>
        <h3 class="font-semibold text-lg mb-2">Docs</h3>
        <p class="text-sm text-slate-400 leading-relaxed mb-4">
          Clear documentation for DNS, email workers, SEO best practices, and integrating third-party
          platforms with your site.
        </p>
        <a href="/docs" class="text-sm text-blue-400 hover:text-blue-300 font-medium">Read docs →</a>
      </article>
    </div>
  </section>

  <!-- ========== EXTRA VALUE (LA/OC + ownership) ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 pb-16">
    <div class="grid md:grid-cols-2 gap-5">
      <div class="card rounded-2xl p-6 md:p-8">
        <div class="text-emerald-400 mb-3"><i class="fas fa-map-marker-alt"></i></div>
        <h3 class="section-title text-xl font-bold mb-2">In-person in LA &amp; OC</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Prefer face-to-face? We offer service calls across Los Angeles and Orange County —
          discovery meetings, design reviews, staff training, and on-site help. Remote clients
          are fully supported online.
        </p>
      </div>
      <div class="card rounded-2xl p-6 md:p-8">
        <div class="text-blue-400 mb-3"><i class="fas fa-key"></i></div>
        <h3 class="section-title text-xl font-bold mb-2">You own the code &amp; data</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Built in-house. Source, assets, and deploy config are yours — not locked inside a page builder
          you rent forever. You dream. We code.
        </p>
      </div>
    </div>
  </section>

  <!-- ========== FINAL CTA ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 pb-20">
    <div class="card rounded-3xl p-8 md:p-12 text-center relative overflow-hidden">
      <div class="absolute inset-0 bg-gradient-to-br from-blue-600/10 via-transparent to-violet-600/10 pointer-events-none"></div>
      <div class="relative">
        <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
          Ready to Claim Your Online Presence?
        </h2>
        <p class="text-slate-400 max-w-xl mx-auto mb-8 leading-relaxed">
          Stop losing customers to unclaimed listings. Let’s build the website that ties everything
          together and gets you found.
        </p>
        <div class="flex flex-col sm:flex-row items-center justify-center gap-3 sm:gap-4">
          <a href="/contact" class="cta-primary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl">
            Contact Us Today
          </a>
          <a href="/tools/Domain_Search" class="cta-secondary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl">
            Search a Domain
          </a>
        </div>
      </div>
    </div>
  </section>

<div class="announcement-banner">
  <div class="banner-container">
    <div class="banner-text" id="bannerText"></div>
  </div>
</div>

<style>
.announcement-banner {
  width: 100%;
  height: 45px;
  background: linear-gradient(135deg, #0a0a0f, #0a0a0f);
  color: white;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 24px;
  font-weight: bold;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  position: relative;
  box-shadow: 0 2px 8px rgba(0,0,0,0.2);
  margin: 10px auto;
  border-radius: 4px;
}

.banner-container {
  width: 100%;
  height: 100%;
  position: relative;
}

.banner-text {
  position: absolute;
  width: 100%;
  text-align: center;
  padding: 0 20px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;

  /* Initial state */
  opacity: 0;
  transform: translateX(50px); /* Start slightly to the right */
  transition: all 0.7s cubic-bezier(0.4, 0, 0.2, 1);
}

/* Active state - visible and centered */
.banner-text.active {
  opacity: 1;
  transform: translateX(0);
}

/* Previous slide (for outgoing) */
.banner-text.out {
  opacity: 0;
  transform: translateX(-50px);
}
</style>

<script>
// Messages - edit these freely
const messages = [
  "🤖 Cloudflare AI",
  "GitHub for Version Control",
  "Google Business Claimed & Linked",
  "Facebook Optimization",
  "Rank #1 on Google",
  "Fine Tuned SEO Strategies",
  "Search Engine Optimized",
  "Analytics Engines",
  "Email Tracking Pixels",
  "Click Tracking",
  "Generate Email Templates",
  "Generate Keywords",
  "Generate Meta Tags",
  "Custom Smart AI Bots",
  "Email Automation",
  "Send Custom Emails",
  "Advanced Dashboards",
  "American Made Technology",
  "24/7 Live Developer Support",
  "You own the Source Code",
  "Custom Builds shipped World Wide"
];

let currentIndex = 0;
const bannerText = document.getElementById('bannerText');

function showMessage(index) {
  bannerText.innerHTML = messages[index];
  bannerText.classList.add('active');
}

function nextMessage() {
  const currentText = bannerText;

  // Start outgoing animation
  currentText.classList.add('out');

  setTimeout(() => {
    currentText.classList.remove('active', 'out');

    // Move to next message
    currentIndex = (currentIndex + 1) % messages.length;
    showMessage(currentIndex);
  }, 700); // Match transition duration
}

// Initialize first message
showMessage(0);

// Auto-rotate every 4.2 seconds
setInterval(nextMessage, 4200);
</script>
  <!-- Domain result modal -->
  <div id="domain-modal" class="domain-modal-backdrop" role="dialog" aria-modal="true" aria-labelledby="domain-modal-title" hidden>
    <div class="domain-modal">
      <div class="flex items-start justify-between gap-3 mb-4">
        <div class="flex items-center gap-3">
          <div id="domain-modal-icon" class="w-11 h-11 rounded-xl flex items-center justify-center text-lg bg-emerald-500/15 text-emerald-400">
            <i class="fas fa-check-circle"></i>
          </div>
          <h2 id="domain-modal-title" class="section-title text-xl font-bold">Domain Available!</h2>
        </div>
        <button type="button" id="domain-modal-close" class="text-slate-500 hover:text-white w-9 h-9 rounded-lg hover:bg-white/5" aria-label="Close">
          <i class="fas fa-times"></i>
        </button>
      </div>
      <p id="domain-modal-message" class="text-slate-300 text-sm leading-relaxed mb-6">
        Great news! <strong class="text-white" id="domain-modal-name">example.com</strong> is available for registration.
      </p>
      <div class="flex flex-col sm:flex-row gap-3">
        <a id="domain-modal-register" href="/register" class="cta-primary flex-1 text-center font-semibold py-3 rounded-xl text-sm">
          Register this domain
        </a>
        <button type="button" id="domain-modal-dismiss" class="cta-secondary flex-1 font-semibold py-3 rounded-xl text-sm">
          Search again
        </button>
      </div>
      <p class="text-xs text-slate-500 mt-4 text-center">
        Availability is checked via public DNS and is not a guarantee of registration success.
      </p>
    </div>
  </div>

  <!-- ========== FOOTER ========== -->
  <footer class="border-t border-white/10 py-10">
    <!--=== visitor counter ===-->
      <div id="my-visitor-counter"></div>
<script
  src="https://visitor-counter.registermysite.com/widget.js"
  data-container="my-visitor-counter"
></script>
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="flex flex-col md:flex-row md:items-start justify-between gap-8 mb-8">
        <div>
          <div class="flex items-center gap-2 mb-3">
           <!-- <div class="w-8 h-8 rounded-lg bg-gradient-to-br from-blue-500 to-violet-600 flex items-center justify-center font-bold text-white text-sm">R</div>
            <span class="font-semibold">registermysite.com</span> -->
          </div>
          <p class="text-sm text-slate-500 max-w-xs">Web development for multi-platform business presence. Domains, design, SEO, and email.</br>
          Register your website to start linking your accounts and Rank higher in search results against your competitors. Claim, Link and Rank. </p>
        </div>
        <div class="grid grid-cols-2 sm:grid-cols-3 gap-8 text-sm">
          <div>
            <div class="text-slate-400 font-medium mb-3">Product</div>
            <ul class="space-y-2 text-slate-500">
              <li><a href="/services" class="hover:text-blue-400">Services</a></li>
              <li><a href="/pricing" class="hover:text-blue-400">Pricing</a></li>
              <li><a href="/tools" class="hover:text-blue-400">Tools</a></li>
              <li><a href="/templates" class="hover:text-blue-400">Templates</a></li>
            </ul>
          </div>
          <div>
            <div class="text-slate-400 font-medium mb-3">Company</div>
            <ul class="space-y-2 text-slate-500">
              <li><a href="/docs" class="hover:text-blue-400">Docs</a></li>
              <li><a href="/api" class="hover:text-blue-400">API</a></li>
              <li><a href="/contact" class="hover:text-blue-400">Contact</a></li>
              <li><a href="/login" class="hover:text-blue-400">Login</a></li>
              <li><a href="/sitemap.html" class="hover:text-blue-400">Site Map</a></li>
            </ul>
          </div>
          <div>
            <div class="text-slate-400 font-medium mb-3">Contact</div>
            <ul class="space-y-2 text-slate-500">
              <li><a href="tel:+15627514597" class="hover:text-blue-400">(562) 751-4597</a></li>
              <li><a href="/cdn-cgi/l/email-protection#6e070008012e1c0b09071d1a0b1c03171d071a0b400d0103" class="hover:text-blue-400"><span class="__cf_email__" data-cfemail="9bf2f5fdf4dbe9fefcf2e8effee9f6e2e8f2effeb5f8f4f6">[email&#160;protected]</span></a></li>
            </ul>
          <img src="https://uploads.registermysite.com/applist.webp" alt="Venmo, CashApp, Zelle, Paypal payment methods accepted" id="PaymentLogo" style="max-width: 100%; height: auto;">
          </div>
        </div>
      </div>
       <a href="https://x.com/diyregistry" class="logo-circle" title="X.com">
  <img src="https://uploads.registermysite.com/favicon-x.png" alt="X" />
</a>
<a href="https://youtube.com/@RegisterMySite" href="https://www.youtube.com/channel/UCwwGNwZJ5JizhMoFU_Z-WOw" class="logo-circle" title="YouTube">
  <img src="https://uploads.registermysite.com/favicon-youtube.png" alt="YT" />
</a>
<a href="https://yelp.com/RegisterMySite" class="logo-circle" title="yelp">
  <img src="https://uploads.registermysite.com/yelp-icon.png" alt="yelp" />
</a>
<a href="https://www.tiktok.com/@registermysite?_r=1&_t=ZP-98fvlLBUhji" class="logo-circle" title="TikTok">
  <img src="https://uploads.registermysite.com/favicon-tiktok.png" alt="TikTok" />
</a>
<a href="https://instagram.com/RegisterMySite" class="logo-circle" title="InstaGram">
  <img src="https://uploads.registermysite.com/favicon-instagram.png" alt="Instagram" />
</a>
<a href="https://github.com/RegisterMySite-com" class="logo-circle" title="GitHub">
  <img src="https://uploads.registermysite.com/github-icon.jpeg" alt="GitHub" />
</a>
<a href="https://google.registermysite.com/Google-Business-Profile" class="logo-circle" title="Google">
  <img src="https://uploads.registermysite.com/google-icon.jpeg" alt="Google" />
</a>
<a href="https://www.facebook.com/profile.php?id=61592420500053&mibextid=ZbWKwL" class="logo-circle" title="Facebook">
  <img src="https://uploads.registermysite.com/facebook-icon.png" alt="Facebook" />
</a>
                <!-- Logo -->
        <a href="/" class="flex items-center gap-3 shrink-0">
          <div class="flex items-center gap-3">
        <img src="https://uploads.registermysite.com/registermysite.jpg" alt="Logo" class="h-10 w-10 rounded-xl object-cover bg-white/20">

          <div class="leading-tight">
            <span class="text-lg font-bold tracking-tight">RegisterMySite</span><span class="text-blue-400">.com</span>
          </div>
        </a>
            </div>
    </div>
  </footer>
<script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script>
  window.RMS_CHAT = {
    url: "https://ai.registermysite.com",
    title: "RegisterMySite AI",
    position: "right",   // or "left"
    openOnLoad: true,
    buttonLabel: "Chat"
  };
</script>
<script src="https://registermysite.com/ai-chat-widget.js" defer></script>
  <script>
    /* —— Mobile nav —— */
    const menuBtn = document.getElementById('menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');
    const menuIcon = document.getElementById('menu-icon');
    const toolsToggle = document.getElementById('tools-toggle');
    const toolsSub = document.getElementById('tools-sub');
    const toolsChevron = document.getElementById('tools-chevron');

    menuBtn.addEventListener('click', () => {
      const open = mobileMenu.classList.toggle('open');
      menuBtn.setAttribute('aria-expanded', open ? 'true' : 'false');
      menuIcon.className = open ? 'fas fa-times text-lg' : 'fas fa-bars text-lg';
      if (!open) {
        toolsSub.classList.remove('open');
        toolsChevron.style.transform = '';
      }
    });

    toolsToggle.addEventListener('click', () => {
      const open = toolsSub.classList.toggle('open');
      toolsChevron.style.transform = open ? 'rotate(180deg)' : '';
    });

    /* —— Domain search (Google DNS-over-HTTPS, same idea as Domain_Search) —— */
    const form = document.getElementById('hero-domain-form');
    const input = document.getElementById('hero-domain-input');
    const btn = document.getElementById('hero-domain-btn');
    const hint = document.getElementById('hero-domain-hint');
    const modal = document.getElementById('domain-modal');
    const modalTitle = document.getElementById('domain-modal-title');
    const modalMessage = document.getElementById('domain-modal-message');
    const modalName = document.getElementById('domain-modal-name');
    const modalIcon = document.getElementById('domain-modal-icon');
    const modalRegister = document.getElementById('domain-modal-register');
    const modalClose = document.getElementById('domain-modal-close');
    const modalDismiss = document.getElementById('domain-modal-dismiss');

    function normalizeDomain(raw) {
      let d = (raw || '').trim().toLowerCase();
      d = d.replace(/^https?:\/\//, '').replace(/^www\./, '').split('/')[0].split('?')[0];
      return d;
    }

    function isValidDomain(d) {
      return /^[a-z0-9]([a-z0-9-]{0,61}[a-z0-9])?(\.[a-z0-9]([a-z0-9-]{0,61}[a-z0-9])?)+$/i.test(d);
    }

    /** NXDOMAIN / no answers ≈ available; answers present ≈ taken */
    async function checkViaGoogleDNS(domain) {
      const url = `https://dns.google/resolve?name=${encodeURIComponent(domain)}&type=A`;
      const res = await fetch(url, { headers: { Accept: 'application/dns-json' } });
      if (!res.ok) throw new Error('DNS lookup failed');
      const data = await res.json();
      // Status 3 = NXDOMAIN (available). Status 0 with Answer = registered.
      if (data.Status === 3) return { available: true };
      if (data.Status === 0 && data.Answer && data.Answer.length > 0) return { available: false };
      // No answer records often means not resolving (treat as likely available)
      if (data.Status === 0 && (!data.Answer || data.Answer.length === 0)) return { available: true };
      return { available: false };
    }

    function openModal({ available, domain }) {
      modal.hidden = false;
      requestAnimationFrame(() => modal.classList.add('open'));

      if (available) {
        modalTitle.textContent = 'Domain Available!';
        modalIcon.className = 'w-11 h-11 rounded-xl flex items-center justify-center text-lg bg-emerald-500/15 text-emerald-400';
        modalIcon.innerHTML = '<i class="fas fa-check-circle"></i>';
        modalMessage.innerHTML = `Great news! <strong class="text-white" id="domain-modal-name">${escapeHtml(domain)}</strong> is available for registration.`;
        modalRegister.href = `https://registermysite.com/register?domain=${encodeURIComponent(domain)}`;
        modalRegister.style.display = '';
        modalRegister.textContent = 'Register this domain';
      } else {
        modalTitle.textContent = 'Domain Taken';
        modalIcon.className = 'w-11 h-11 rounded-xl flex items-center justify-center text-lg bg-amber-500/15 text-amber-400';
        modalIcon.innerHTML = '<i class="fas fa-times-circle"></i>';
        modalMessage.innerHTML = `<strong class="text-white">${escapeHtml(domain)}</strong> appears to be registered. Try another name or check advanced tools for alternatives.`;
        modalRegister.href = `/tools/Domain_Search`;
        modalRegister.textContent = 'Try advanced search';
      }
    }

    function closeModal() {
      modal.classList.remove('open');
      setTimeout(() => { modal.hidden = true; }, 200);
    }

    function escapeHtml(s) {
      return String(s)
        .replace(/&/g, '&amp;')
        .replace(/</g, '&lt;')
        .replace(/>/g, '&gt;')
        .replace(/"/g, '&quot;');
    }

    form.addEventListener('submit', async (e) => {
      e.preventDefault();
      const domain = normalizeDomain(input.value);
      hint.textContent = '';

      if (!domain) {
        hint.textContent = 'Enter a domain name to search.';
        hint.className = 'text-sm text-amber-400 mb-6 min-h-[1.25rem]';
        return;
      }
      if (!isValidDomain(domain)) {
        hint.textContent = 'Enter a valid domain like example.com';
        hint.className = 'text-sm text-amber-400 mb-6 min-h-[1.25rem]';
        return;
      }

      btn.disabled = true;
      btn.innerHTML = '<i class="fas fa-spinner fa-spin mr-1.5"></i> Checking…';
      hint.textContent = `Checking ${domain}…`;
      hint.className = 'text-sm text-slate-400 mb-6 min-h-[1.25rem]';

      try {
        const result = await checkViaGoogleDNS(domain);
        hint.textContent = '';
        openModal({ available: result.available, domain });
      } catch (err) {
        console.error(err);
        hint.textContent = 'Lookup failed. Please try again or use Domain Search tools.';
        hint.className = 'text-sm text-red-400 mb-6 min-h-[1.25rem]';
      } finally {
        btn.disabled = false;
        btn.innerHTML = '<i class="fas fa-search mr-1.5"></i> Search';
      }
    });

    modalClose.addEventListener('click', closeModal);
    modalDismiss.addEventListener('click', () => {
      closeModal();
      input.focus();
    });
    modal.addEventListener('click', (e) => {
      if (e.target === modal) closeModal();
    });
    document.addEventListener('keydown', (e) => {
      if (e.key === 'Escape' && modal.classList.contains('open')) closeModal();
    });
  </script>
</body>
</html></doc></services><optional><doc title="Domain Search Tool" desc="Check domain availability"><!DOCTYPE html>
<html lang="en">
<head>
<script async src="https://www.googletagmanager.com/gtag/js?id=G-GMLQJKKPPP"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-GMLQJKKPPP');
</script>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Domain WHOIS & Availability Lookup — registermysite.com</title>
    <meta name="description" content="Free instant domain availability check and WHOIS lookup. Find your perfect domain name.">

    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Space+Grotesk:wght@500;600;700&display=swap');

        body {
            font-family: 'Inter', system-ui, sans-serif;
            background: #0a0a0f;
            color: #e2e8f0;
        }

        .section-title {
            font-family: 'Space Grotesk', sans-serif;
        }

        .gradient-text {
            background: linear-gradient(135deg, #60a5fa, #a78bfa, #f472b6);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .card {
            background: rgba(255,255,255,0.03);
            border: 1px solid rgba(255,255,255,0.08);
        }

        input {
            background: rgba(0,0,0,0.45);
            border: 1px solid rgba(255,255,255,0.12);
            color: #e2e8f0;
            border-radius: 12px;
            padding: 16px 20px;
            font-size: 1.1rem;
            width: 100%;
            transition: all 0.2s;
        }

        input:focus {
            outline: none;
            border-color: #60a5fa;
            box-shadow: 0 0 0 3px rgba(96,165,250,0.15);
        }

        .available { color: #34d399; }
        .taken { color: #f87171; }
    </style>
</head>
<body class="min-h-screen">

    <!-- Header -->
    <header class="border-b border-white/10 sticky top-0 z-50 backdrop-blur-xl bg-black/60">
        <div class="max-w-4xl mx-auto px-6 py-5 flex items-center justify-between">
            <div class="flex items-center gap-3">
                <div class="w-10 h-10 rounded-xl bg-gradient-to-br from-blue-500 to-violet-600 flex items-center justify-center font-bold text-white text-lg">R</div>
                <div>
                    <span class="text-xl font-bold tracking-tight">registermysite</span><span class="text-blue-400">.com</span>
                </div>
            </div>
            <nav class="hidden sm:flex items-center gap-6 text-sm font-medium">
                <a href="tools.html" class="hover:text-blue-400 transition">All Tools</a>
                <a href="templates.html" class="hover:text-blue-400 transition">Templates</a>
            </nav>
        </div>
    </header>

    <!-- Hero -->
    <section class="max-w-4xl mx-auto px-6 pt-16 pb-10 text-center">
        <p class="text-blue-400 font-semibold tracking-widest uppercase text-sm mb-3">Free Domain Tool</p>
        <h1 class="section-title text-4xl md:text-5xl font-bold mb-4">
            Domain WHOIS &<br>
            <span class="gradient-text">Availability Lookup</span>
        </h1>
        <p class="text-slate-400 text-lg max-w-2xl mx-auto">
            Instantly check if a domain is available and view full WHOIS registration details.
        </p>
    </section>

    <!-- Search Box -->
    <section class="max-w-3xl mx-auto px-6 pb-12">
        <div class="card rounded-3xl p-8 md:p-10">
            <h2 class="text-2xl font-semibold mb-6 text-center">Find Your Domain</h2>

            <div class="flex flex-col sm:flex-row gap-3">
                <input type="text" id="domain-input"
                       placeholder="Enter domain name (e.g. example.com)"
                       class="flex-1">
                <button id="search-btn"
                        class="bg-gradient-to-r from-blue-600 to-violet-600 hover:from-blue-500 hover:to-violet-500 text-white font-semibold px-8 py-4 rounded-xl transition whitespace-nowrap">
                    <i class="fas fa-search mr-2"></i> Search Domain
                </button>
            </div>

            <!-- Results -->
            <div id="result" class="mt-10 hidden">
                <h2 id="status-title" class="text-2xl font-bold mb-2"></h2>
                <p id="status-message" class="text-slate-400 mb-6"></p>

                <a id="register-link"
                   class="inline-flex items-center gap-2 bg-emerald-600 hover:bg-emerald-500 text-white font-semibold px-6 py-3 rounded-xl transition mb-6"
                   style="display:none;" href="#" target="_blank">
                    <i class="fas fa-check-circle"></i>
                    Register This Domain Now
                </a>

                <div id="whois-details"
                     class="bg-black/40 border border-white/10 rounded-2xl p-5 font-mono text-sm text-slate-300 whitespace-pre-wrap leading-relaxed">
                </div>
            </div>
        </div>
    </section>

    <!-- TLD Info -->
    <section class="max-w-3xl mx-auto px-6 pb-20">
        <div class="card rounded-3xl p-8 md:p-10 text-center">
            <h2 class="section-title text-3xl font-bold mb-4">
                Find Your <span class="gradient-text">Perfect Domain</span>
            </h2>
            <p class="text-slate-400 mb-8 max-w-xl mx-auto">
                Search available domains across hundreds of top-level domains (TLDs).
            </p>

            <div class="bg-blue-500/10 border border-blue-500/20 rounded-2xl p-6 text-left mb-8">
                <h3 class="text-blue-400 font-semibold text-lg mb-3">What is a TLD?</h3>
                <p class="text-slate-300 text-sm leading-relaxed mb-3">
                    A <strong>Top-Level Domain (TLD)</strong> is the last part of a domain name — the letters after the final dot.
                    Examples include <strong>.com</strong>, <strong>.org</strong>, <strong>.net</strong>, and newer options like
                    <strong>.app</strong>, <strong>.dev</strong>, <strong>.shop</strong>, and <strong>.xyz</strong>.
                </p>
                <p class="text-slate-400 text-sm">
                    TLDs help define the purpose or brand of a website. With hundreds of options available,
                    you can find a domain that perfectly matches your project or business.
                </p>
            </div>

            <a href="/tools/TLDsearch.html"
               class="inline-flex items-center gap-2 bg-gradient-to-r from-blue-600 to-violet-600 hover:from-blue-500 hover:to-violet-500 text-white font-semibold px-8 py-4 rounded-2xl transition text-lg">
                Browse All Supported TLDs
                <i class="fas fa-arrow-right"></i>
            </a>

            <p class="text-sm text-slate-500 mt-6">
                Explore the full interactive list of TLDs with registry details, search, sorting, and pagination.
            </p>
        </div>

        <div class="text-center mt-10">
            <a href="tools.html" class="text-blue-400 hover:text-blue-300 transition text-sm font-medium">
                ← Back to All Tools
            </a>
        </div>
    </section>

    <!-- Footer -->
    <footer class="border-t border-white/10 py-12">
        <div class="max-w-4xl mx-auto px-6 flex flex-col md:flex-row items-center justify-between gap-6 text-sm text-slate-500">
            <div class="flex items-center gap-2">
                <div class="w-8 h-8 rounded-lg bg-gradient-to-br from-blue-500 to-violet-600 flex items-center justify-center font-bold text-white text-sm">R</div>
                <span>registermysite.com</span>
            </div>
            <p>© 2026 registermysite.com — Domain WHOIS Lookup</p>
            <p class="italic">You dream. We code.</p>
        </div>
        <p class="text-center text-xs text-slate-600 mt-6 max-w-2xl mx-auto px-6">
            WHOIS data powered by public APIs • Direct registration available through registermysite.com • For assistance email <a href="/cdn-cgi/l/email-protection" class="__cf_email__" data-cfemail="4e3d2f222b3d0e3c2b29273d3a2b3c23373d273a2b602d2123">[email&#160;protected]</a>
        </p>
    </footer>

    <script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script>
        document.getElementById('search-btn').addEventListener('click', performLookup);
        document.getElementById('domain-input').addEventListener('keypress', (e) => {
            if (e.key === 'Enter') performLookup();
        });

        async function performLookup() {
            let input = document.getElementById('domain-input').value.trim();
            if (!input) {
                alert('Please enter a domain name!');
                return;
            }

            input = input.toLowerCase();
            const resultDiv = document.getElementById('result');
            const statusTitle = document.getElementById('status-title');
            const statusMessage = document.getElementById('status-message');
            const registerLink = document.getElementById('register-link');
            const detailsDiv = document.getElementById('whois-details');

            resultDiv.classList.remove('hidden');
            statusTitle.textContent = 'Looking up...';
            statusTitle.className = 'text-2xl font-bold mb-2 text-blue-400';
            statusMessage.textContent = 'Fetching WHOIS data from public API...';
            registerLink.style.display = 'none';
            detailsDiv.textContent = '';

            try {
                const response = await fetch(`https://www.whatismyip.net/whois/?domain=${encodeURIComponent(input)}`);
                if (!response.ok) throw new Error('API request failed');
                const data = await response.json();

                const isAvailable = data.ldhName === null || (data.events && data.events[0] && data.events[0].eventDate === null);

                if (isAvailable) {
                    statusTitle.textContent = 'Domain Available!';
                    statusTitle.className = 'text-2xl font-bold mb-2 available';
                    statusMessage.textContent = `Great news! ${input} is available for registration.`;
                    registerLink.style.display = 'inline-flex';
                    // Direct registration link on registermysite.com
                    registerLink.href = `https://registermysite.com/register?domain=${encodeURIComponent(input)}`;
                    registerLink.innerHTML = `<i class="fas fa-check-circle"></i> Register ${input} Now`;
                } else {
                    statusTitle.textContent = 'Domain is Taken';
                    statusTitle.className = 'text-2xl font-bold mb-2 taken';
                    statusMessage.textContent = `${input} is already registered.`;
                }

                let details = '';
                if (data.entities) {
                    const registrarEntity = data.entities.find(e => e.roles && e.roles.includes('registrar'));
                    if (registrarEntity && registrarEntity.vcardArray && registrarEntity.vcardArray[1]) {
                        const registrarName = registrarEntity.vcardArray[1].find(item => item[0] === 'fn')?.[3];
                        if (registrarName && registrarName !== 'N/A') details += `Registrar: ${registrarName}\n`;
                    }
                }

                if (data.events) {
                    const registrationEvent = data.events.find(e => e.eventAction === 'registration');
                    if (registrationEvent && registrationEvent.eventDate) {
                        details += `Created: ${new Date(registrationEvent.eventDate).toLocaleDateString()}\n`;
                    }
                    const expirationEvent = data.events.find(e => e.eventAction === 'expiration');
                    if (expirationEvent && expirationEvent.eventDate) {
                        details += `Expires: ${new Date(expirationEvent.eventDate).toLocaleDateString()}\n`;
                    }
                    const lastChangedEvent = data.events.find(e => e.eventAction === 'last changed');
                    if (lastChangedEvent && lastChangedEvent.eventDate) {
                        details += `Updated: ${new Date(lastChangedEvent.eventDate).toLocaleDateString()}\n`;
                    }
                }

                detailsDiv.textContent = details || 'No additional details available.';
            } catch (error) {
                console.error(error);
                statusTitle.textContent = 'Limited Data Available';
                statusTitle.className = 'text-2xl font-bold mb-2 text-amber-400';
                statusMessage.innerHTML = `Could not retrieve full WHOIS details for ${input}.<br>You can still attempt registration.`;
                registerLink.style.display = 'inline-flex';
                // Direct registration link on registermysite.com
                registerLink.href = `https://registermysite.com/register?domain=${encodeURIComponent(input)}`;
                registerLink.innerHTML = `<i class="fas fa-check-circle"></i> Register ${input} Now`;
                detailsDiv.textContent = 'Public API may be temporarily limited.';
            }
        }
    </script>
</body>
</html></doc><doc title="Contact / Start Project" desc="Reach the team to begin a project"><!DOCTYPE html>
<html lang="en">
<head>

  <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence</title>
    <meta name="description" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">
    <meta name="title" content="RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <!-- Preconnect to the domain-->
    <link rel="preconnect" href="https://visitor-counter.registermysite.com" crossorigin>
    <!-- Optional: Preload the script for even faster loading -->
    <link rel="preload" href="https://visitor-counter.registermysite.com/widget.js" as="script">
  <!-- Favicons and install icons -->
  <link rel="icon" href="/assets/icons/favicon.ico" sizes="any">
  <link rel="icon" type="image/png" sizes="16x16" href="/assets/icons/favicon-16x16.jpg">
  <link rel="icon" type="image/png" sizes="32x32" href="/assets/icons/favicon-32x32.jpg">
  <link rel="icon" type="image/png" sizes="48x48" href="/assets/icons/favicon-48x48.jpg">
  <link rel="icon" type="image/png" sizes="96x96" href="/assets/icons/favicon-96x96.jpg">
  <link rel="apple-touch-icon" sizes="180x180" href="/assets/icons/apple-touch-icon.jpg">
  <link rel="manifest" href="/assets/manifest.json">

  <!-- Open Graph / Facebook -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://registermysite.com">
  <meta property="og:title" content="RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence">
  <meta property="og:description" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">
  <meta property="og:image" content="https://registermysite.com/assets/og-card.jpg">
  <meta property="og:image:width" content="1200">
  <meta property="og:image:height" content="630">
  <meta property="og:image:alt" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">

  <!-- Twitter -->
  <meta property="twitter:card" content="summary_large_image">
  <meta property="twitter:url" content="https://registermysite.com">
  <meta property="twitter:title" content="RegisterMySite.com | Web Development Agency for Multi-Platform Business Presence">
  <meta property="twitter:description" content="RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.">
  <meta property="twitter:image" content="https://registermysite.com/assets/og-card.jpg">

  <!-- Structured data -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "WebApplication",
    "name": "Register My Site",
    "url": "https://registermysite.com",
    "description": "RegisterMySite.com builds professional websites that claim, link, and optimize your Yelp, Google Business, and other listings for maximum SEO and online visibility.",
    "applicationCategory": "UtilitiesApplication",
    "operatingSystem": "Any (Windows, macOS, Android, iOS, Linux, ChromeOS)",
    "isAccessibleForFree": true,
    "offers": {
      "@type": "Offer",
      "price": "0",
      "priceCurrency": "USD"
    }
  }
  </script>

  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Space+Grotesk:wght@500;600;700&display=swap');

    body {
      font-family: 'Inter', system-ui, sans-serif;
      background: #0a0a0f;
      color: #e2e8f0;
    }

    .section-title {
      font-family: 'Space Grotesk', sans-serif;
    }

    .gradient-text {
      background: linear-gradient(135deg, #60a5fa, #a78bfa, #f472b6);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
    }

    .card {
      background: rgba(255, 255, 255, 0.03);
      border: 1px solid rgba(255, 255, 255, 0.08);
      transition: border-color 0.2s, background 0.2s;
    }

    .card:hover {
      border-color: rgba(96, 165, 250, 0.28);
      background: rgba(255, 255, 255, 0.045);
    }

    /* Hero background image + overlay */
    .hero {
            background: linear-gradient(rgba(0,123,255,0.88), rgba(0,80,200,0.88)), url('https://uploads.registermysite.com/registermysite.gif?auto=format&fit=crop&w=1920&q=80') center/cover no-repeat;
            color: white;
            text-align: center;
            padding: 160px 20px 120px;
            position: relative;
        }

    .cta-primary {
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: #fff;
      transition: background 0.25s ease, transform 0.2s ease, box-shadow 0.25s ease;
    }

    .cta-primary {
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: #fff;
      transition: background 0.25s ease, transform 0.2s ease, box-shadow 0.25s ease;
    }

    .cta-primary:hover {
      background: linear-gradient(135deg, #22d3ee, #a78bfa);
      transform: translateY(-2px);
      box-shadow: 0 12px 32px rgba(96, 165, 250, 0.35);
    }

    .cta-secondary {
      background: transparent;
      color: #e2e8f0;
      border: 1px solid rgba(255, 255, 255, 0.2);
      transition: background 0.25s ease, border-color 0.25s ease, color 0.25s ease, transform 0.2s ease;
    }

    .cta-secondary:hover {
      background: rgba(96, 165, 250, 0.15);
      border-color: #60a5fa;
      color: #93c5fd;
      transform: translateY(-2px);
    }

    /* Domain search bar */
    .domain-search-wrap {
      display: flex;
      flex-direction: column;
      gap: 0.75rem;
      width: 100%;
      max-width: 36rem;
    }

    @media (min-width: 640px) {
      .domain-search-wrap {
        flex-direction: row;
        align-items: stretch;
      }
    }

    .domain-search-input {
      flex: 1;
      background: rgba(0, 0, 0, 0.55);
      border: 1px solid rgba(255, 255, 255, 0.14);
      color: #e2e8f0;
      border-radius: 12px;
      padding: 0.9rem 1.1rem;
      font-size: 1rem;
      transition: border-color 0.2s, box-shadow 0.2s;
      min-width: 0;
    }

    .domain-search-input:focus {
      outline: none;
      border-color: #60a5fa;
      box-shadow: 0 0 0 3px rgba(96, 165, 250, 0.2);
    }

    .domain-search-input::placeholder {
      color: #64748b;
    }

    .domain-search-btn {
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: #fff;
      border: none;
      border-radius: 12px;
      padding: 0.9rem 1.4rem;
      font-weight: 600;
      font-size: 0.95rem;
      cursor: pointer;
      white-space: nowrap;
      transition: background 0.25s ease, transform 0.2s ease, box-shadow 0.25s ease;
    }

    .domain-search-btn:hover:not(:disabled) {
      background: linear-gradient(135deg, #22d3ee, #a78bfa);
      transform: translateY(-1px);
      box-shadow: 0 10px 28px rgba(96, 165, 250, 0.35);
    }

    .domain-search-btn:disabled {
      opacity: 0.65;
      cursor: wait;
    }

    /* Result modal */
    .domain-modal-backdrop {
      position: fixed;
      inset: 0;
      background: rgba(0, 0, 0, 0.7);
      backdrop-filter: blur(6px);
      z-index: 100;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 1.25rem;
      opacity: 0;
      visibility: hidden;
      transition: opacity 0.2s ease, visibility 0.2s ease;
    }

    .domain-modal-backdrop.open {
      opacity: 1;
      visibility: visible;
    }

    .domain-modal {
      background: #12121a;
      border: 1px solid rgba(255, 255, 255, 0.12);
      border-radius: 1.25rem;
      padding: 1.75rem 1.5rem;
      width: 100%;
      max-width: 26rem;
      box-shadow: 0 24px 64px rgba(0, 0, 0, 0.5);
      transform: translateY(12px);
      transition: transform 0.2s ease;
    }

    .domain-modal-backdrop.open .domain-modal {
      transform: translateY(0);
    }

    /* Mobile menu */
    .mobile-panel {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.35s ease;
    }

    .mobile-panel.open {
      max-height: 640px;
    }

    .mobile-sub {
      max-height: 0;
      overflow: hidden;
      transition: max-height 0.3s ease;
    }

    .mobile-sub.open {
      max-height: 280px;
    }

    .nav-link {
      transition: color 0.15s ease;
    }

    .nav-link:hover {
      color: #60a5fa;
    }

    .status-pill {
      display: inline-flex;
      align-items: center;
      gap: 0.35rem;
      font-size: 0.75rem;
      padding: 0.35rem 0.7rem;
      border-radius: 9999px;
      background: rgba(16, 185, 129, 0.12);
      border: 1px solid rgba(16, 185, 129, 0.25);
      color: #6ee7b7;
    }

    .step-num {
      width: 2.25rem;
      height: 2.25rem;
      border-radius: 9999px;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      font-weight: 700;
      font-size: 0.9rem;
      background: linear-gradient(135deg, #3b82f6, #8b5cf6);
      color: white;
      flex-shrink: 0;
    }
    .logo-circle {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 36px;          /* tiny size */
  height: 36px;
  border-radius: 50%;   /* makes it a circle */
  overflow: hidden;     /* clips the image to the circle */
  background: white;    /* optional fallback */
  border: 2px solid rgba(255,255,255,0.3);
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}

.logo-circle img {
  width: 100%;
  height: 100%;
  object-fit: cover;    /* fills the circle nicely */
}

.logo-circle:hover {
  transform: scale(1.08);
  box-shadow: 0 0 0 3px rgba(79, 70, 229, 0.3);
}
  </style>
   <!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-GMLQJKKPPP"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-GMLQJKKPPP');
</script>
</head>
<body class="min-h-screen">

  <!-- ========== NAVIGATION ========== -->
  <header class="border-b border-white/10 sticky top-0 z-50 backdrop-blur-xl bg-black/70">
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="flex items-center justify-between h-16">
        <!-- Logo -->
        <a href="/" class="flex items-center gap-3 shrink-0">
          <img src="https://uploads.registermysite.com/registermysite.gif" alt="Logo" class="h-10 w-10 rounded-xl object-cover bg-white/20">
        <div>
         <span class="text-2xl font-bold tracking-tight">RegisterMySite</span><span class="text-blue-400">.com</span>
          </div>
        </a>

        <!-- Desktop nav -->
        <nav class="hidden lg:flex items-center gap-7 text-sm font-medium">
          <a href="/services" class="nav-link text-slate-300">Services</a>
          <a href="/pricing" class="nav-link text-slate-300">Pricing</a>
          <div class="relative group">
            <button type="button" class="nav-link text-slate-300 inline-flex items-center gap-1.5">
              Tools <i class="fas fa-chevron-down text-[10px] opacity-70"></i>
            </button>
            <div class="invisible opacity-0 group-hover:visible group-hover:opacity-100 transition-all duration-200 absolute top-full left-0 pt-2 w-56">
              <div class="card rounded-xl py-2 shadow-xl shadow-black/40">
                <a href="/tools/Domain_Search" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">Domain Search</a>
                <a href="/tools/TLDsearch" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">TLD Search</a>
                <a href="/tools/QR_Code" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">QR Code</a>
                <a href="/tools/og-preview" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">OG Preview</a>
                <a href="https://meta-gen.registermysite.com" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">Meta Generator</a>
                <a href="https://email-gen.registermysite.com" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">Email Template Generator</a>
                <a href="https://ai.editor.registermysite.com" class="block px-4 py-2.5 text-sm text-slate-300 hover:bg-white/5 hover:text-blue-400">HTML Website Generator</a>
                <a href="/tools" class="block px-4 py-2.5 text-sm text-blue-400 hover:bg-white/5 border-t border-white/10 mt-1 pt-2.5">All tools →</a>
              </div>
            </div>
          </div>
          <a href="/Web_Design" class="nav-link text-slate-300">Web Design</a>
          <a href="/Business_Email.html" class="nav-link text-slate-300">Business Email</a>
          <a href="/docs" class="nav-link text-slate-300">Docs</a>
          <a href="/contact" class="nav-link text-slate-300">Contact</a>
          <a href="/login" class="cta-primary text-sm font-semibold px-4 py-2 rounded-lg">Login</a>
        </nav>

        <!-- Mobile hamburger -->
        <button type="button" id="menu-btn" class="lg:hidden w-10 h-10 flex items-center justify-center rounded-lg border border-white/10 text-slate-200 hover:border-blue-400/40" aria-label="Open menu" aria-expanded="false">
          <i class="fas fa-bars text-lg" id="menu-icon"></i>
        </button>
      </div>

      <!-- Mobile dropdown panel -->
      <div id="mobile-menu" class="mobile-panel lg:hidden border-t border-white/10">
        <nav class="py-3 flex flex-col text-sm font-medium">
          <a href="/services" class="px-2 py-3 text-slate-300 hover:text-blue-400">Services</a>
          <a href="/pricing" class="px-2 py-3 text-slate-300 hover:text-blue-400">Pricing</a>

          <!-- Expandable: Tools -->
          <button type="button" id="tools-toggle" class="px-2 py-3 text-left text-slate-300 hover:text-blue-400 flex items-center justify-between w-full">
            <span>Tools</span>
            <i class="fas fa-chevron-down text-xs transition-transform duration-200" id="tools-chevron"></i>
          </button>
          <div id="tools-sub" class="mobile-sub bg-black/30 rounded-xl mx-1 mb-1">
            <a href="/tools/Domain_Search" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">Domain Search</a>
            <a href="/tools/TLDsearch" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">TLD Search</a>
            <a href="/tools/QR_Code" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">QR Code Generator</a>
            <a href="/tools/og-image" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">OG Image Generator</a>
            <a href="/tools/og-preview" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">OG Preview</a>
            <a href="https://meta-gen.registermysite.com" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">Meta Title Generator</a>
            <a href="https://email-gen.registermysite.com" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">Email Template Generator</a>
            <a href="https://ai.editor.registermysite.com" class="block px-4 py-2.5 text-slate-400 hover:text-blue-400">HTML Website Generator</a>
            <a href="/tools" class="block px-4 py-2.5 text-blue-400 hover:text-blue-300">View all tools →</a>
          </div>

          <a href="/Web_Design" class="px-2 py-3 text-slate-300 hover:text-blue-400">Web Design</a>
          <a href="/SEO_Optimization" class="px-2 py-3 text-slate-300 hover:text-blue-400">SEO</a>
          <a href="/Business_Email" class="px-2 py-3 text-slate-300 hover:text-blue-400">Business Email</a>
          <a href="/docs" class="px-2 py-3 text-slate-300 hover:text-blue-400">Docs</a>
          <a href="/contact" class="px-2 py-3 text-slate-300 hover:text-blue-400">Contact</a>
          <a href="/login" class="mx-2 mt-2 mb-3 cta-primary text-center font-semibold py-3 rounded-xl">Login / Sign up</a>
        </nav>
      </div>
    </div>
  </header>

  <!-- ========== HERO ========== -->
  <section class="hero">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-24 w-full relative z-10">
      <p class="text-blue-400 text-sm font-semibold tracking-wide uppercase mb-4">Web development agency</p>
      <h1 class="section-title text-4xl sm:text-5xl md:text-6xl font-bold leading-tight mb-5 max-w-3xl">
        Your Business <span class="gradient-text">Online</span>
      </h1>
      <p class="text-slate-300 text-lg md:text-xl max-w-2xl leading-relaxed mb-8">
        Multi-platform presence that ties your website, Google Business, Yelp, and social profiles together —
        so customers find a professional brand, not scattered listings.
      </p>

      <form id="hero-domain-form" class="domain-search-wrap mb-4" autocomplete="off">
        <input
          type="text"
          id="hero-domain-input"
          class="domain-search-input"
          placeholder="Search a domain — e.g. example.com"
          spellcheck="false"
          autocapitalize="off"
          inputmode="url"
          aria-label="Domain name to search"
        />
        <button type="submit" id="hero-domain-btn" class="domain-search-btn">
          <i class="fas fa-search mr-1.5"></i> Search
        </button>
      </form>
      <p id="hero-domain-hint" class="text-sm text-slate-500 mb-6 min-h-[1.25rem]"></p>

      <div class="flex flex-col sm:flex-row gap-3 sm:gap-4 mb-10">
        <a href="/contact" class="cta-secondary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl text-base">
          <i class="fas fa-envelope"></i>
          Contact Us Today
        </a>
        <a href="/tools/Domain_Search" class="cta-secondary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl text-base text-sm">
          Advanced domain tools →
        </a>
      </div>

      <!-- Platform status pills -->
      <div class="flex flex-wrap gap-2">
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Yelp · Claimed &amp; Linked</span>
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Google Business · Claimed &amp; Linked</span>
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Facebook · Connected</span>
        <span class="status-pill"><i class="fas fa-check text-[10px]"></i> Instagram · Connected</span>
      </div>
    </div>
  </section>

  <!-- ========== CORE SERVICES ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-20">
    <div class="text-center mb-12">
      <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
        Everything Your Business Needs <span class="gradient-text">Online</span>
      </h2>
      <p class="text-slate-400 text-base md:text-lg max-w-2xl mx-auto leading-relaxed">
        From domain setup to SEO-powered websites and professional email — we handle the technical side
        so you can focus on customers.
      </p>
    </div>

    <div class="grid sm:grid-cols-2 gap-5">
      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-blue-500/15 text-blue-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-globe"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">Domain &amp; DNS Setup</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          We register or connect your domain, configure DNS records correctly, and make sure everything
          points to your new site with zero downtime.
        </p>
      </article>

      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-violet-500/15 text-violet-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-magnifying-glass"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">SEO Optimization</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Technical SEO, schema markup, local SEO, and strategic linking of all your platform profiles
          so Google ranks your business higher.
        </p>
      </article>

      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-pink-500/15 text-pink-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-palette"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">Web Design &amp; Templates</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Beautiful, conversion-focused designs and ready-to-use industry templates. Fully responsive
          and mobile-first for every device.
        </p>
      </article>

      <article class="card rounded-2xl p-6 md:p-7">
        <div class="w-11 h-11 rounded-xl bg-emerald-500/15 text-emerald-400 flex items-center justify-center text-lg mb-4">
          <i class="fas fa-envelope"></i>
        </div>
        <h3 class="section-title text-xl font-bold mb-2">Custom Business Email</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Professional email addresses (@yourbusiness.com) with auto-reply workers that respond
          instantly while you’re busy with customers.
        </p>
      </article>
    </div>
  </section>

  <!-- ========== HOW IT WORKS ========== -->
  <section class="border-y border-white/5 bg-white/[0.015]">
    <div class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-20">
      <div class="text-center mb-12">
        <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
          How It <span class="gradient-text">Works</span>
        </h2>
        <p class="text-slate-400 max-w-xl mx-auto">
          From scattered listings to a fully connected online presence in four simple steps.
        </p>
      </div>

      <div class="grid md:grid-cols-2 gap-5">
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">1</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Audit Your Listings</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              We find every unclaimed or disconnected profile for your business across major platforms.
            </p>
          </div>
        </div>
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">2</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Build Your Website</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              Choose a template or go custom. We create a site that showcases your business and services.
            </p>
          </div>
        </div>
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">3</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Claim &amp; Link Everything</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              We claim your Yelp, Google Business, and other accounts and link them back to your new website.
            </p>
          </div>
        </div>
        <div class="card rounded-2xl p-6 flex gap-4">
          <span class="step-num">4</span>
          <div>
            <h3 class="font-semibold text-lg mb-1">Launch &amp; Rank</h3>
            <p class="text-sm text-slate-400 leading-relaxed">
              DNS, SEO, emails, and analytics go live. Your business becomes discoverable and professional.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ========== TOOLS ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 py-16 md:py-20">
    <div class="text-center mb-12">
      <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
        Built for Developers &amp; <span class="gradient-text">Businesses</span>
      </h2>
      <p class="text-slate-400 max-w-xl mx-auto">
        Powerful tools when you need them, simple when you don’t.
      </p>
    </div>

    <div class="grid md:grid-cols-3 gap-5">
      <article class="card rounded-2xl p-6">
        <div class="text-blue-400 text-xl mb-3"><i class="fas fa-file-lines"></i></div>
        <h3 class="font-semibold text-lg mb-2">Templates</h3>
        <p class="text-sm text-slate-400 leading-relaxed mb-4">
          Browse dozens of industry-ready website templates. Restaurants, salons, contractors, clinics —
          pick one and customize in minutes.
        </p>
        <a href="/templates" class="text-sm text-blue-400 hover:text-blue-300 font-medium">Browse templates →</a>
      </article>
      <article class="card rounded-2xl p-6">
        <div class="text-violet-400 text-xl mb-3"><i class="fas fa-bolt"></i></div>
        <h3 class="font-semibold text-lg mb-2">API</h3>
        <p class="text-sm text-slate-400 leading-relaxed mb-4">
          Programmatically manage domains, DNS, listings, and site deployments. Perfect for agencies
          managing multiple client sites.
        </p>
        <a href="/api" class="text-sm text-blue-400 hover:text-blue-300 font-medium">API reference →</a>
      </article>
      <article class="card rounded-2xl p-6">
        <div class="text-pink-400 text-xl mb-3"><i class="fas fa-book"></i></div>
        <h3 class="font-semibold text-lg mb-2">Docs</h3>
        <p class="text-sm text-slate-400 leading-relaxed mb-4">
          Clear documentation for DNS, email workers, SEO best practices, and integrating third-party
          platforms with your site.
        </p>
        <a href="/docs" class="text-sm text-blue-400 hover:text-blue-300 font-medium">Read docs →</a>
      </article>
    </div>
  </section>

  <!-- ========== EXTRA VALUE (LA/OC + ownership) ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 pb-16">
    <div class="grid md:grid-cols-2 gap-5">
      <div class="card rounded-2xl p-6 md:p-8">
        <div class="text-emerald-400 mb-3"><i class="fas fa-map-marker-alt"></i></div>
        <h3 class="section-title text-xl font-bold mb-2">In-person in LA &amp; OC</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Prefer face-to-face? We offer service calls across Los Angeles and Orange County —
          discovery meetings, design reviews, staff training, and on-site help. Remote clients
          are fully supported online.
        </p>
      </div>
      <div class="card rounded-2xl p-6 md:p-8">
        <div class="text-blue-400 mb-3"><i class="fas fa-key"></i></div>
        <h3 class="section-title text-xl font-bold mb-2">You own the code &amp; data</h3>
        <p class="text-sm text-slate-400 leading-relaxed">
          Built in-house. Source, assets, and deploy config are yours — not locked inside a page builder
          you rent forever. You dream. We code.
        </p>
      </div>
    </div>
  </section>

  <!-- ========== FINAL CTA ========== -->
  <section class="max-w-6xl mx-auto px-4 sm:px-6 pb-20">
    <div class="card rounded-3xl p-8 md:p-12 text-center relative overflow-hidden">
      <div class="absolute inset-0 bg-gradient-to-br from-blue-600/10 via-transparent to-violet-600/10 pointer-events-none"></div>
      <div class="relative">
        <h2 class="section-title text-3xl md:text-4xl font-bold mb-4">
          Ready to Claim Your Online Presence?
        </h2>
        <p class="text-slate-400 max-w-xl mx-auto mb-8 leading-relaxed">
          Stop losing customers to unclaimed listings. Let’s build the website that ties everything
          together and gets you found.
        </p>
        <div class="flex flex-col sm:flex-row items-center justify-center gap-3 sm:gap-4">
          <a href="/contact" class="cta-primary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl">
            Contact Us Today
          </a>
          <a href="/tools/Domain_Search" class="cta-secondary inline-flex items-center justify-center gap-2 font-semibold px-7 py-3.5 rounded-xl">
            Search a Domain
          </a>
        </div>
      </div>
    </div>
  </section>

<div class="announcement-banner">
  <div class="banner-container">
    <div class="banner-text" id="bannerText"></div>
  </div>
</div>

<style>
.announcement-banner {
  width: 100%;
  height: 45px;
  background: linear-gradient(135deg, #0a0a0f, #0a0a0f);
  color: white;
  font-family: Arial, Helvetica, sans-serif;
  font-size: 24px;
  font-weight: bold;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
  position: relative;
  box-shadow: 0 2px 8px rgba(0,0,0,0.2);
  margin: 10px auto;
  border-radius: 4px;
}

.banner-container {
  width: 100%;
  height: 100%;
  position: relative;
}

.banner-text {
  position: absolute;
  width: 100%;
  text-align: center;
  padding: 0 20px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;

  /* Initial state */
  opacity: 0;
  transform: translateX(50px); /* Start slightly to the right */
  transition: all 0.7s cubic-bezier(0.4, 0, 0.2, 1);
}

/* Active state - visible and centered */
.banner-text.active {
  opacity: 1;
  transform: translateX(0);
}

/* Previous slide (for outgoing) */
.banner-text.out {
  opacity: 0;
  transform: translateX(-50px);
}
</style>

<script>
// Messages - edit these freely
const messages = [
  "🤖 Cloudflare AI",
  "GitHub for Version Control",
  "Google Business Claimed & Linked",
  "Facebook Optimization",
  "Rank #1 on Google",
  "Fine Tuned SEO Strategies",
  "Search Engine Optimized",
  "Analytics Engines",
  "Email Tracking Pixels",
  "Click Tracking",
  "Generate Email Templates",
  "Generate Keywords",
  "Generate Meta Tags",
  "Custom Smart AI Bots",
  "Email Automation",
  "Send Custom Emails",
  "Advanced Dashboards",
  "American Made Technology",
  "24/7 Live Developer Support",
  "You own the Source Code",
  "Custom Builds shipped World Wide"
];

let currentIndex = 0;
const bannerText = document.getElementById('bannerText');

function showMessage(index) {
  bannerText.innerHTML = messages[index];
  bannerText.classList.add('active');
}

function nextMessage() {
  const currentText = bannerText;

  // Start outgoing animation
  currentText.classList.add('out');

  setTimeout(() => {
    currentText.classList.remove('active', 'out');

    // Move to next message
    currentIndex = (currentIndex + 1) % messages.length;
    showMessage(currentIndex);
  }, 700); // Match transition duration
}

// Initialize first message
showMessage(0);

// Auto-rotate every 4.2 seconds
setInterval(nextMessage, 4200);
</script>
  <!-- Domain result modal -->
  <div id="domain-modal" class="domain-modal-backdrop" role="dialog" aria-modal="true" aria-labelledby="domain-modal-title" hidden>
    <div class="domain-modal">
      <div class="flex items-start justify-between gap-3 mb-4">
        <div class="flex items-center gap-3">
          <div id="domain-modal-icon" class="w-11 h-11 rounded-xl flex items-center justify-center text-lg bg-emerald-500/15 text-emerald-400">
            <i class="fas fa-check-circle"></i>
          </div>
          <h2 id="domain-modal-title" class="section-title text-xl font-bold">Domain Available!</h2>
        </div>
        <button type="button" id="domain-modal-close" class="text-slate-500 hover:text-white w-9 h-9 rounded-lg hover:bg-white/5" aria-label="Close">
          <i class="fas fa-times"></i>
        </button>
      </div>
      <p id="domain-modal-message" class="text-slate-300 text-sm leading-relaxed mb-6">
        Great news! <strong class="text-white" id="domain-modal-name">example.com</strong> is available for registration.
      </p>
      <div class="flex flex-col sm:flex-row gap-3">
        <a id="domain-modal-register" href="/register" class="cta-primary flex-1 text-center font-semibold py-3 rounded-xl text-sm">
          Register this domain
        </a>
        <button type="button" id="domain-modal-dismiss" class="cta-secondary flex-1 font-semibold py-3 rounded-xl text-sm">
          Search again
        </button>
      </div>
      <p class="text-xs text-slate-500 mt-4 text-center">
        Availability is checked via public DNS and is not a guarantee of registration success.
      </p>
    </div>
  </div>

  <!-- ========== FOOTER ========== -->
  <footer class="border-t border-white/10 py-10">
    <!--=== visitor counter ===-->
      <div id="my-visitor-counter"></div>
<script
  src="https://visitor-counter.registermysite.com/widget.js"
  data-container="my-visitor-counter"
></script>
    <div class="max-w-6xl mx-auto px-4 sm:px-6">
      <div class="flex flex-col md:flex-row md:items-start justify-between gap-8 mb-8">
        <div>
          <div class="flex items-center gap-2 mb-3">
           <!-- <div class="w-8 h-8 rounded-lg bg-gradient-to-br from-blue-500 to-violet-600 flex items-center justify-center font-bold text-white text-sm">R</div>
            <span class="font-semibold">registermysite.com</span> -->
          </div>
          <p class="text-sm text-slate-500 max-w-xs">Web development for multi-platform business presence. Domains, design, SEO, and email.</br>
          Register your website to start linking your accounts and Rank higher in search results against your competitors. Claim, Link and Rank. </p>
        </div>
        <div class="grid grid-cols-2 sm:grid-cols-3 gap-8 text-sm">
          <div>
            <div class="text-slate-400 font-medium mb-3">Product</div>
            <ul class="space-y-2 text-slate-500">
              <li><a href="/services" class="hover:text-blue-400">Services</a></li>
              <li><a href="/pricing" class="hover:text-blue-400">Pricing</a></li>
              <li><a href="/tools" class="hover:text-blue-400">Tools</a></li>
              <li><a href="/templates" class="hover:text-blue-400">Templates</a></li>
            </ul>
          </div>
          <div>
            <div class="text-slate-400 font-medium mb-3">Company</div>
            <ul class="space-y-2 text-slate-500">
              <li><a href="/docs" class="hover:text-blue-400">Docs</a></li>
              <li><a href="/api" class="hover:text-blue-400">API</a></li>
              <li><a href="/contact" class="hover:text-blue-400">Contact</a></li>
              <li><a href="/login" class="hover:text-blue-400">Login</a></li>
              <li><a href="/sitemap.html" class="hover:text-blue-400">Site Map</a></li>
            </ul>
          </div>
          <div>
            <div class="text-slate-400 font-medium mb-3">Contact</div>
            <ul class="space-y-2 text-slate-500">
              <li><a href="tel:+15627514597" class="hover:text-blue-400">(562) 751-4597</a></li>
              <li><a href="/cdn-cgi/l/email-protection#c2abaca4ad82b0a7a5abb1b6a7b0afbbb1abb6a7eca1adaf" class="hover:text-blue-400"><span class="__cf_email__" data-cfemail="472e292128073522202e343322352a3e342e33226924282a">[email&#160;protected]</span></a></li>
            </ul>
          <img src="https://uploads.registermysite.com/applist.webp" alt="Venmo, CashApp, Zelle, Paypal payment methods accepted" id="PaymentLogo" style="max-width: 100%; height: auto;">
          </div>
        </div>
      </div>
       <a href="https://x.com/diyregistry" class="logo-circle" title="X.com">
  <img src="https://uploads.registermysite.com/favicon-x.png" alt="X" />
</a>
<a href="https://youtube.com/@RegisterMySite" href="https://www.youtube.com/channel/UCwwGNwZJ5JizhMoFU_Z-WOw" class="logo-circle" title="YouTube">
  <img src="https://uploads.registermysite.com/favicon-youtube.png" alt="YT" />
</a>
<a href="https://yelp.com/RegisterMySite" class="logo-circle" title="yelp">
  <img src="https://uploads.registermysite.com/yelp-icon.png" alt="yelp" />
</a>
<a href="https://www.tiktok.com/@registermysite?_r=1&_t=ZP-98fvlLBUhji" class="logo-circle" title="TikTok">
  <img src="https://uploads.registermysite.com/favicon-tiktok.png" alt="TikTok" />
</a>
<a href="https://instagram.com/RegisterMySite" class="logo-circle" title="InstaGram">
  <img src="https://uploads.registermysite.com/favicon-instagram.png" alt="Instagram" />
</a>
<a href="https://github.com/RegisterMySite-com" class="logo-circle" title="GitHub">
  <img src="https://uploads.registermysite.com/github-icon.jpeg" alt="GitHub" />
</a>
<a href="https://google.registermysite.com/Google-Business-Profile" class="logo-circle" title="Google">
  <img src="https://uploads.registermysite.com/google-icon.jpeg" alt="Google" />
</a>
<a href="https://www.facebook.com/profile.php?id=61592420500053&mibextid=ZbWKwL" class="logo-circle" title="Facebook">
  <img src="https://uploads.registermysite.com/facebook-icon.png" alt="Facebook" />
</a>
                <!-- Logo -->
        <a href="/" class="flex items-center gap-3 shrink-0">
          <div class="flex items-center gap-3">
        <img src="https://uploads.registermysite.com/registermysite.jpg" alt="Logo" class="h-10 w-10 rounded-xl object-cover bg-white/20">

          <div class="leading-tight">
            <span class="text-lg font-bold tracking-tight">RegisterMySite</span><span class="text-blue-400">.com</span>
          </div>
        </a>
            </div>
    </div>
  </footer>
<script data-cfasync="false" src="/cdn-cgi/scripts/5c5dd728/cloudflare-static/email-decode.min.js"></script><script>
  window.RMS_CHAT = {
    url: "https://ai.registermysite.com",
    title: "RegisterMySite AI",
    position: "right",   // or "left"
    openOnLoad: true,
    buttonLabel: "Chat"
  };
</script>
<script src="https://registermysite.com/ai-chat-widget.js" defer></script>
  <script>
    /* —— Mobile nav —— */
    const menuBtn = document.getElementById('menu-btn');
    const mobileMenu = document.getElementById('mobile-menu');
    const menuIcon = document.getElementById('menu-icon');
    const toolsToggle = document.getElementById('tools-toggle');
    const toolsSub = document.getElementById('tools-sub');
    const toolsChevron = document.getElementById('tools-chevron');

    menuBtn.addEventListener('click', () => {
      const open = mobileMenu.classList.toggle('open');
      menuBtn.setAttribute('aria-expanded', open ? 'true' : 'false');
      menuIcon.className = open ? 'fas fa-times text-lg' : 'fas fa-bars text-lg';
      if (!open) {
        toolsSub.classList.remove('open');
        toolsChevron.style.transform = '';
      }
    });

    toolsToggle.addEventListener('click', () => {
      const open = toolsSub.classList.toggle('open');
      toolsChevron.style.transform = open ? 'rotate(180deg)' : '';
    });

    /* —— Domain search (Google DNS-over-HTTPS, same idea as Domain_Search) —— */
    const form = document.getElementById('hero-domain-form');
    const input = document.getElementById('hero-domain-input');
    const btn = document.getElementById('hero-domain-btn');
    const hint = document.getElementById('hero-domain-hint');
    const modal = document.getElementById('domain-modal');
    const modalTitle = document.getElementById('domain-modal-title');
    const modalMessage = document.getElementById('domain-modal-message');
    const modalName = document.getElementById('domain-modal-name');
    const modalIcon = document.getElementById('domain-modal-icon');
    const modalRegister = document.getElementById('domain-modal-register');
    const modalClose = document.getElementById('domain-modal-close');
    const modalDismiss = document.getElementById('domain-modal-dismiss');

    function normalizeDomain(raw) {
      let d = (raw || '').trim().toLowerCase();
      d = d.replace(/^https?:\/\//, '').replace(/^www\./, '').split('/')[0].split('?')[0];
      return d;
    }

    function isValidDomain(d) {
      return /^[a-z0-9]([a-z0-9-]{0,61}[a-z0-9])?(\.[a-z0-9]([a-z0-9-]{0,61}[a-z0-9])?)+$/i.test(d);
    }

    /** NXDOMAIN / no answers ≈ available; answers present ≈ taken */
    async function checkViaGoogleDNS(domain) {
      const url = `https://dns.google/resolve?name=${encodeURIComponent(domain)}&type=A`;
      const res = await fetch(url, { headers: { Accept: 'application/dns-json' } });
      if (!res.ok) throw new Error('DNS lookup failed');
      const data = await res.json();
      // Status 3 = NXDOMAIN (available). Status 0 with Answer = registered.
      if (data.Status === 3) return { available: true };
      if (data.Status === 0 && data.Answer && data.Answer.length > 0) return { available: false };
      // No answer records often means not resolving (treat as likely available)
      if (data.Status === 0 && (!data.Answer || data.Answer.length === 0)) return { available: true };
      return { available: false };
    }

    function openModal({ available, domain }) {
      modal.hidden = false;
      requestAnimationFrame(() => modal.classList.add('open'));

      if (available) {
        modalTitle.textContent = 'Domain Available!';
        modalIcon.className = 'w-11 h-11 rounded-xl flex items-center justify-center text-lg bg-emerald-500/15 text-emerald-400';
        modalIcon.innerHTML = '<i class="fas fa-check-circle"></i>';
        modalMessage.innerHTML = `Great news! <strong class="text-white" id="domain-modal-name">${escapeHtml(domain)}</strong> is available for registration.`;
        modalRegister.href = `https://registermysite.com/register?domain=${encodeURIComponent(domain)}`;
        modalRegister.style.display = '';
        modalRegister.textContent = 'Register this domain';
      } else {
        modalTitle.textContent = 'Domain Taken';
        modalIcon.className = 'w-11 h-11 rounded-xl flex items-center justify-center text-lg bg-amber-500/15 text-amber-400';
        modalIcon.innerHTML = '<i class="fas fa-times-circle"></i>';
        modalMessage.innerHTML = `<strong class="text-white">${escapeHtml(domain)}</strong> appears to be registered. Try another name or check advanced tools for alternatives.`;
        modalRegister.href = `/tools/Domain_Search`;
        modalRegister.textContent = 'Try advanced search';
      }
    }

    function closeModal() {
      modal.classList.remove('open');
      setTimeout(() => { modal.hidden = true; }, 200);
    }

    function escapeHtml(s) {
      return String(s)
        .replace(/&/g, '&amp;')
        .replace(/</g, '&lt;')
        .replace(/>/g, '&gt;')
        .replace(/"/g, '&quot;');
    }

    form.addEventListener('submit', async (e) => {
      e.preventDefault();
      const domain = normalizeDomain(input.value);
      hint.textContent = '';

      if (!domain) {
        hint.textContent = 'Enter a domain name to search.';
        hint.className = 'text-sm text-amber-400 mb-6 min-h-[1.25rem]';
        return;
      }
      if (!isValidDomain(domain)) {
        hint.textContent = 'Enter a valid domain like example.com';
        hint.className = 'text-sm text-amber-400 mb-6 min-h-[1.25rem]';
        return;
      }

      btn.disabled = true;
      btn.innerHTML = '<i class="fas fa-spinner fa-spin mr-1.5"></i> Checking…';
      hint.textContent = `Checking ${domain}…`;
      hint.className = 'text-sm text-slate-400 mb-6 min-h-[1.25rem]';

      try {
        const result = await checkViaGoogleDNS(domain);
        hint.textContent = '';
        openModal({ available: result.available, domain });
      } catch (err) {
        console.error(err);
        hint.textContent = 'Lookup failed. Please try again or use Domain Search tools.';
        hint.className = 'text-sm text-red-400 mb-6 min-h-[1.25rem]';
      } finally {
        btn.disabled = false;
        btn.innerHTML = '<i class="fas fa-search mr-1.5"></i> Search';
      }
    });

    modalClose.addEventListener('click', closeModal);
    modalDismiss.addEventListener('click', () => {
      closeModal();
      input.focus();
    });
    modal.addEventListener('click', (e) => {
      if (e.target === modal) closeModal();
    });
    document.addEventListener('keydown', (e) => {
      if (e.key === 'Escape' && modal.classList.contains('open')) closeModal();
    });
  </script>
</body>
</html></doc></optional></project>
