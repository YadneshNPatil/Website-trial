<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Yadnesh Patil – D365 F&O Functional Consultant</title>
<meta name="description" content="Yadnesh Naresh Patil – Microsoft Dynamics 365 Finance & Operations Functional Consultant. SCM, Procurement & Inventory. Mumbai, India. Open to remote." />
<link href="https://fonts.googleapis.com/css2?family=Cabinet+Grotesk:wght@400;500;700;800&family=Instrument+Serif:ital@0;1&family=DM+Sans:wght@300;400;500&display=swap" rel="stylesheet" />
<style>
*, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }

:root {
  --ink:       #0e1117;
  --ink2:      #1c2230;
  --ink3:      #2e3a50;
  --muted:     #6b7a94;
  --faint:     #a8b4c8;
  --rule:      #dde3ee;
  --bg:        #f7f8fc;
  --surface:   #ffffff;
  --blue:      #1a56db;
  --blue-lt:   #e8effe;
  --blue-mid:  #3b72f5;
  --teal:      #0d9488;
  --teal-lt:   #e0f5f3;
  --amber:     #d97706;
  --amber-lt:  #fef3c7;
  --green:     #16a34a;
  --green-lt:  #dcfce7;
}

html { scroll-behavior: smooth; font-size: 16px; }

body {
  font-family: 'DM Sans', sans-serif;
  background: var(--bg);
  color: var(--ink);
  line-height: 1.65;
  -webkit-font-smoothing: antialiased;
}

/* ── NAV ── */
nav {
  position: sticky; top: 0; z-index: 200;
  background: rgba(247,248,252,0.92);
  backdrop-filter: blur(16px);
  border-bottom: 1px solid var(--rule);
  display: flex; align-items: center; justify-content: space-between;
  padding: 0 clamp(1.5rem, 5vw, 4rem);
  height: 60px;
}
.nav-logo {
  font-family: 'Cabinet Grotesk', sans-serif;
  font-weight: 800; font-size: 1.05rem;
  color: var(--ink); text-decoration: none;
  letter-spacing: -0.02em;
  display: flex; align-items: center; gap: 8px;
}
.nav-logo-dot { width: 8px; height: 8px; border-radius: 50%; background: var(--blue-mid); display: inline-block; }
.nav-links { display: flex; gap: 1.75rem; list-style: none; }
.nav-links a {
  font-size: 0.82rem; font-weight: 500; letter-spacing: 0.03em;
  color: var(--muted); text-decoration: none;
  text-transform: uppercase; transition: color 0.18s;
}
.nav-links a:hover { color: var(--ink); }
.nav-cta {
  background: var(--ink); color: #fff !important;
  padding: 7px 16px; border-radius: 6px;
  font-size: 0.8rem !important;
  transition: background 0.18s !important;
}
.nav-cta:hover { background: var(--blue) !important; color: #fff !important; }

/* ── HERO ── */
.hero {
  min-height: calc(100vh - 60px);
  display: grid;
  grid-template-columns: 1fr 1fr;
  align-items: center;
  gap: 3rem;
  padding: clamp(3rem, 8vw, 6rem) clamp(1.5rem, 5vw, 4rem);
  max-width: 1200px;
  margin: 0 auto;
}
.hero-left { max-width: 560px; }
.hero-eyebrow {
  display: inline-flex; align-items: center; gap: 8px;
  font-size: 0.72rem; font-weight: 500; letter-spacing: 0.1em;
  text-transform: uppercase; color: var(--blue);
  margin-bottom: 1.4rem;
}
.hero-eyebrow::before {
  content: ''; width: 28px; height: 2px;
  background: var(--blue-mid); display: inline-block;
}
.hero h1 {
  font-family: 'Cabinet Grotesk', sans-serif;
  font-size: clamp(2.4rem, 5.5vw, 4.2rem);
  font-weight: 800;
  line-height: 1.05;
  letter-spacing: -0.03em;
  color: var(--ink);
  margin-bottom: 1.2rem;
}
.hero h1 em {
  font-family: 'Instrument Serif', serif;
  font-style: italic;
  font-weight: 400;
  color: var(--blue-mid);
}
.hero-sub {
  font-size: 1.05rem;
  color: var(--muted);
  font-weight: 300;
  line-height: 1.75;
  max-width: 480px;
  margin-bottom: 2rem;
}
.hero-tags { display: flex; flex-wrap: wrap; gap: 8px; margin-bottom: 2.2rem; }
.htag {
  background: var(--blue-lt);
  color: var(--blue);
  font-size: 0.72rem; font-weight: 500;
  padding: 5px 12px; border-radius: 100px;
  letter-spacing: 0.02em;
}
.htag.teal { background: var(--teal-lt); color: var(--teal); }
.htag.amber { background: var(--amber-lt); color: var(--amber); }
.hero-actions { display: flex; gap: 1rem; flex-wrap: wrap; }
.btn-primary {
  background: var(--ink); color: #fff;
  padding: 0.8rem 1.8rem; border-radius: 8px;
  text-decoration: none; font-weight: 500; font-size: 0.88rem;
  transition: background 0.18s, transform 0.12s;
  display: inline-flex; align-items: center; gap: 6px;
}
.btn-primary:hover { background: var(--blue); transform: translateY(-1px); }
.btn-outline {
  border: 1.5px solid var(--rule); color: var(--ink);
  padding: 0.8rem 1.8rem; border-radius: 8px;
  text-decoration: none; font-weight: 500; font-size: 0.88rem;
  transition: border-color 0.18s, transform 0.12s;
  display: inline-flex; align-items: center; gap: 6px;
  background: var(--surface);
}
.btn-outline:hover { border-color: var(--blue-mid); transform: translateY(-1px); }

.hero-right { position: relative; }
.hero-photo-wrap {
  position: relative;
  max-width: 420px; margin-left: auto;
}
.hero-photo-wrap::before {
  content: '';
  position: absolute;
  inset: -12px -12px 12px 12px;
  background: var(--blue-lt);
  border-radius: 20px;
  z-index: 0;
}
.hero-photo-placeholder {
  position: relative; z-index: 1;
  width: 100%; aspect-ratio: 4/5;
  border-radius: 16px;
  background: linear-gradient(145deg, #e8effe 0%, #dde8ff 100%);
  border: 1px solid var(--rule);
  display: flex; flex-direction: column;
  align-items: center; justify-content: center;
  gap: 10px; color: var(--muted); font-size: 0.82rem;
  overflow: hidden;
}
.hero-photo-placeholder img {
  width: 100%; height: 100%; object-fit: cover;
  display: block;
}
.hero-card {
  position: absolute;
  bottom: -1.5rem; left: -2rem;
  background: var(--surface);
  border: 1px solid var(--rule);
  border-radius: 12px;
  padding: 1rem 1.2rem;
  z-index: 2;
  box-shadow: 0 4px 24px rgba(14,17,23,0.08);
}
.hero-card-label { font-size: 0.7rem; color: var(--faint); text-transform: uppercase; letter-spacing: 0.07em; margin-bottom: 3px; }
.hero-card-val { font-family: 'Cabinet Grotesk', sans-serif; font-weight: 700; font-size: 1.4rem; color: var(--ink); letter-spacing: -0.02em; }
.avail-badge {
  position: absolute; top: 1.5rem; right: -1rem;
  background: var(--green-lt);
  border: 1px solid #bbf7d0;
  border-radius: 100px;
  padding: 6px 14px;
  font-size: 0.72rem; font-weight: 600;
  color: var(--green);
  display: flex; align-items: center; gap: 6px;
  z-index: 2;
}
.avail-dot { width: 7px; height: 7px; border-radius: 50%; background: var(--green); animation: blink 2s infinite; }
@keyframes blink { 0%,100%{opacity:1} 50%{opacity:0.4} }

/* ── MARQUEE STRIP ── */
.marquee-wrap {
  border-top: 1px solid var(--rule);
  border-bottom: 1px solid var(--rule);
  overflow: hidden;
  padding: 14px 0;
  background: var(--surface);
}
.marquee-track {
  display: flex; gap: 3rem;
  animation: marquee 22s linear infinite;
  white-space: nowrap;
}
@keyframes marquee { from{transform:translateX(0)} to{transform:translateX(-50%)} }
.marquee-item {
  font-size: 0.72rem; font-weight: 500; letter-spacing: 0.1em;
  text-transform: uppercase; color: var(--faint);
  display: flex; align-items: center; gap: 0.75rem;
  flex-shrink: 0;
}
.marquee-item::after { content: '·'; font-size: 1rem; color: var(--rule); }

/* ── SHARED SECTION STYLES ── */
.section { padding: clamp(3.5rem, 8vw, 6rem) clamp(1.5rem, 5vw, 4rem); max-width: 1200px; margin: 0 auto; }
.section-full { padding: clamp(3.5rem, 8vw, 6rem) clamp(1.5rem, 5vw, 4rem); }
.section-full-inner { max-width: 1200px; margin: 0 auto; }
.eyebrow { font-size: 0.72rem; font-weight: 500; letter-spacing: 0.1em; text-transform: uppercase; color: var(--blue); margin-bottom: 0.6rem; display: flex; align-items: center; gap: 8px; }
.eyebrow::before { content:''; width:20px; height:2px; background:var(--blue-mid); }
.section-h { font-family: 'Cabinet Grotesk', sans-serif; font-weight: 800; font-size: clamp(1.8rem,4vw,2.8rem); letter-spacing: -0.025em; line-height: 1.1; color: var(--ink); margin-bottom: 0.75rem; }
.section-desc { color: var(--muted); font-size: 0.95rem; font-weight: 300; max-width: 520px; margin-bottom: 2.5rem; line-height: 1.7; }

/* ── ABOUT ── */
.about-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 4rem; align-items: start; }
.about-body p { color: var(--muted); font-weight: 300; line-height: 1.8; margin-bottom: 1.1rem; font-size: 0.95rem; }
.about-body strong { color: var(--ink); font-weight: 500; }
.about-stats { display: grid; grid-template-columns: 1fr 1fr; gap: 1px; border: 1px solid var(--rule); border-radius: 12px; overflow: hidden; margin-top: 2rem; }
.astat {
  padding: 1.25rem;
  background: var(--surface);
  border-right: 1px solid var(--rule);
  border-bottom: 1px solid var(--rule);
}
.astat:nth-child(2n) { border-right: none; }
.astat:nth-child(3), .astat:nth-child(4) { border-bottom: none; }
.astat-num { font-family: 'Cabinet Grotesk', sans-serif; font-weight: 800; font-size: 1.8rem; color: var(--ink); letter-spacing: -0.03em; display: block; }
.astat-label { font-size: 0.72rem; color: var(--muted); text-transform: uppercase; letter-spacing: 0.07em; }

.edu-block { background: var(--surface); border: 1px solid var(--rule); border-radius: 14px; padding: 1.5rem; }
.edu-block h3 { font-family: 'Cabinet Grotesk', sans-serif; font-weight: 700; font-size: 1rem; margin-bottom: 1rem; color: var(--ink); }
.edu-item { padding: 0.9rem 0; border-bottom: 1px solid var(--rule); }
.edu-item:last-child { border-bottom: none; padding-bottom: 0; }
.edu-deg { font-size: 0.88rem; font-weight: 500; color: var(--ink); margin-bottom: 3px; }
.edu-school { font-size: 0.78rem; color: var(--muted); margin-bottom: 2px; }
.edu-year { font-size: 0.72rem; color: var(--faint); }

/* ── EXPERIENCE ── */
.exp-wrap { background: var(--ink); }
.exp-inner { color: #fff; }
.exp-inner .eyebrow { color: #6ee7f7; }
.exp-inner .eyebrow::before { background: #6ee7f7; }
.exp-inner .section-h { color: #fff; }
.exp-inner .section-desc { color: rgba(255,255,255,0.5); }
.timeline { display: flex; flex-direction: column; gap: 0; }
.tl-item {
  display: grid; grid-template-columns: 200px 1fr;
  gap: 2rem; padding: 2.5rem 0;
  border-bottom: 1px solid rgba(255,255,255,0.07);
  position: relative;
}
.tl-item:last-child { border-bottom: none; }
.tl-left {}
.tl-period { font-size: 0.75rem; color: rgba(255,255,255,0.35); letter-spacing: 0.03em; margin-bottom: 6px; }
.tl-company { font-size: 0.82rem; font-weight: 500; color: #6ee7f7; margin-bottom: 3px; }
.tl-loc { font-size: 0.72rem; color: rgba(255,255,255,0.3); }
.tl-right {}
.tl-role { font-family: 'Cabinet Grotesk', sans-serif; font-weight: 700; font-size: 1.15rem; color: #fff; letter-spacing: -0.01em; margin-bottom: 0.75rem; }
.tl-desc { font-size: 0.85rem; color: rgba(255,255,255,0.55); line-height: 1.75; font-weight: 300; }
.tl-pills { display: flex; flex-wrap: wrap; gap: 6px; margin-top: 1rem; }
.tl-pill { background: rgba(255,255,255,0.07); border: 1px solid rgba(255,255,255,0.1); padding: 4px 11px; border-radius: 100px; font-size: 0.7rem; color: rgba(255,255,255,0.5); }

/* ── SKILLS ── */
.skills-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)); gap: 1rem; }
.skill-card {
  background: var(--surface);
  border: 1px solid var(--rule);
  border-radius: 14px;
  padding: 1.5rem;
  transition: border-color 0.18s, transform 0.15s;
}
.skill-card:hover { border-color: var(--blue-mid); transform: translateY(-2px); }
.sk-icon {
  width: 38px; height: 38px;
  border-radius: 10px;
  display: flex; align-items: center; justify-content: center;
  font-size: 1.1rem; margin-bottom: 0.9rem;
}
.sk-icon.blue { background: var(--blue-lt); }
.sk-icon.teal { background: var(--teal-lt); }
.sk-icon.amber { background: var(--amber-lt); }
.skill-card h3 { font-family: 'Cabinet Grotesk', sans-serif; font-weight: 700; font-size: 0.95rem; color: var(--ink); margin-bottom: 0.4rem; }
.skill-card p { font-size: 0.8rem; color: var(--muted); line-height: 1.6; font-weight: 300; margin-bottom: 0.9rem; }
.sk-tags { display: flex; flex-wrap: wrap; gap: 5px; }
.sk-tag { background: var(--bg); border: 1px solid var(--rule); padding: 3px 9px; border-radius: 100px; font-size: 0.68rem; color: var(--muted); }

/* ── CERTIFICATIONS ── */
.certs-bg { background: var(--blue-lt); }
.certs-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 1rem; }
.cert-card {
  background: var(--surface);
  border: 1px solid var(--rule);
  border-radius: 14px; padding: 1.5rem;
  display: flex; align-items: flex-start; gap: 1rem;
  transition: border-color 0.18s;
}
.cert-card:hover { border-color: var(--blue-mid); }
.cert-icon {
  width: 48px; height: 48px; flex-shrink: 0;
  border-radius: 12px;
  display: flex; align-items: center; justify-content: center;
  font-family: 'Cabinet Grotesk', sans-serif;
  font-weight: 800; font-size: 0.65rem; text-align: center; line-height: 1.3;
}
.cert-icon.done { background: var(--blue-lt); color: var(--blue); border: 1.5px solid #c7d7fb; }
.cert-icon.planned { background: var(--amber-lt); color: var(--amber); border: 1.5px dashed #fcd34d; }
.cert-title { font-size: 0.9rem; font-weight: 500; color: var(--ink); margin-bottom: 3px; }
.cert-sub { font-size: 0.75rem; color: var(--muted); font-weight: 300; line-height: 1.5; }
.cert-badge {
  display: inline-block; margin-top: 7px;
  font-size: 0.65rem; font-weight: 600; letter-spacing: 0.05em;
  text-transform: uppercase; padding: 3px 9px; border-radius: 100px;
}
.cert-badge.planned { background: var(--amber-lt); color: var(--amber); }
.cert-badge.done { background: var(--green-lt); color: var(--green); }

/* ── ARTICLES ── */
.articles-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1rem; }
.article-card {
  background: var(--surface);
  border: 1px solid var(--rule);
  border-radius: 14px; padding: 1.5rem;
  text-decoration: none; display: block;
  transition: border-color 0.18s, transform 0.15s;
}
.article-card:hover { border-color: var(--blue-mid); transform: translateY(-2px); }
.art-cat { font-size: 0.68rem; font-weight: 600; text-transform: uppercase; letter-spacing: 0.08em; color: var(--blue); margin-bottom: 0.5rem; }
.art-title { font-size: 0.92rem; font-weight: 500; color: var(--ink); line-height: 1.45; margin-bottom: 0.5rem; }
.art-meta { font-size: 0.72rem; color: var(--faint); }
.art-arrow { float: right; color: var(--faint); font-size: 1rem; margin-top: -1.5rem; }
.articles-li-cta { display: inline-flex; align-items: center; gap: 6px; margin-top: 1.8rem; color: var(--blue); font-size: 0.88rem; font-weight: 500; text-decoration: none; transition: gap 0.18s; }
.articles-li-cta:hover { gap: 10px; }

/* ── CONTACT ── */
.contact-bg { background: var(--ink); }
.contact-inner { max-width: 700px; }
.contact-inner .eyebrow { color: #6ee7f7; }
.contact-inner .eyebrow::before { background: #6ee7f7; }
.contact-inner .section-h { color: #fff; }
.contact-inner .section-desc { color: rgba(255,255,255,0.45); }
.contact-links { display: flex; flex-wrap: wrap; gap: 0.75rem; }
.contact-link {
  display: inline-flex; align-items: center; gap: 10px;
  padding: 0.8rem 1.4rem;
  border: 1px solid rgba(255,255,255,0.12);
  border-radius: 10px;
  color: rgba(255,255,255,0.7);
  text-decoration: none; font-size: 0.84rem;
  background: rgba(255,255,255,0.04);
  transition: border-color 0.18s, color 0.18s, background 0.18s;
}
.contact-link:hover { border-color: #6ee7f7; color: #fff; background: rgba(255,255,255,0.07); }
.contact-link svg { width: 15px; height: 15px; fill: currentColor; flex-shrink: 0; }

/* ── FOOTER ── */
footer {
  background: #060a10;
  border-top: 1px solid rgba(255,255,255,0.05);
  padding: 1.5rem clamp(1.5rem, 5vw, 4rem);
  display: flex; align-items: center; justify-content: space-between; flex-wrap: wrap; gap: 1rem;
}
.footer-logo { font-family: 'Cabinet Grotesk', sans-serif; font-weight: 800; color: rgba(255,255,255,0.4); font-size: 0.9rem; }
.footer-copy { font-size: 0.72rem; color: rgba(255,255,255,0.2); }
.footer-domain { font-size: 0.72rem; color: rgba(255,255,255,0.2); }

/* ── RESPONSIVE ── */
@media (max-width: 820px) {
  .hero { grid-template-columns: 1fr; min-height: auto; padding-top: 3rem; }
  .hero-right { display: none; }
  .about-grid { grid-template-columns: 1fr; }
  .tl-item { grid-template-columns: 1fr; gap: 0.5rem; }
  .tl-left { display: flex; gap: 1rem; align-items: baseline; }
  .nav-links { display: none; }
}
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <a href="#home" class="nav-logo"><span class="nav-logo-dot"></span> Yadnesh Patil</a>
  <ul class="nav-links">
    <li><a href="#about">About</a></li>
    <li><a href="#experience">Experience</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#articles">Articles</a></li>
    <li><a href="#contact" class="nav-cta">Contact</a></li>
  </ul>
</nav>

<!-- HERO -->
<div id="home">
  <div class="hero">
    <div class="hero-left">
      <div class="hero-eyebrow">D365 F&amp;O Functional Consultant</div>
      <h1>Turning ERP complexity into <em>business clarity.</em></h1>
      <p class="hero-sub">Microsoft Dynamics 365 Finance &amp; Operations specialist with a 6-year foundation in real-world supply chain operations. Based in Mumbai — open to remote engagements globally.</p>
      <div class="hero-tags">
        <span class="htag">D365 F&amp;O</span>
        <span class="htag">SCM &amp; Procurement</span>
        <span class="htag teal">Inventory Management</span>
        <span class="htag teal">AX 2012</span>
        <span class="htag amber">Fit-Gap Analysis</span>
        <span class="htag amber">UAT</span>
      </div>
      <div class="hero-actions">
        <a href="#contact" class="btn-primary">Get in touch →</a>
        <a href="#experience" class="btn-outline">View experience</a>
      </div>
    </div>
    <div class="hero-right">
      <div class="hero-photo-wrap">
        <div class="avail-badge"><span class="avail-dot"></span> Open to remote work</div>
        <div class="hero-photo-placeholder">
          <!-- Replace src below with your actual photo path once hosted -->
          <span style="font-size:0.78rem;color:var(--muted);">Upload your photo here</span>
        </div>
        <div class="hero-card">
          <div class="hero-card-label">Total Experience</div>
          <div class="hero-card-val">7+ Years</div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- MARQUEE -->
<div class="marquee-wrap">
  <div class="marquee-track">
    <span class="marquee-item">D365 Finance &amp; Operations</span>
    <span class="marquee-item">SCM Consulting</span>
    <span class="marquee-item">Procurement Flows</span>
    <span class="marquee-item">Inventory Management</span>
    <span class="marquee-item">AX 2012</span>
    <span class="marquee-item">Fit-Gap Analysis</span>
    <span class="marquee-item">UAT Support</span>
    <span class="marquee-item">Data Migration</span>
    <span class="marquee-item">Master Data Configuration</span>
    <span class="marquee-item">Import Operations</span>
    <span class="marquee-item">Mumbai · Remote Global</span>
    <span class="marquee-item">D365 Finance &amp; Operations</span>
    <span class="marquee-item">SCM Consulting</span>
    <span class="marquee-item">Procurement Flows</span>
    <span class="marquee-item">Inventory Management</span>
    <span class="marquee-item">AX 2012</span>
    <span class="marquee-item">Fit-Gap Analysis</span>
    <span class="marquee-item">UAT Support</span>
    <span class="marquee-item">Data Migration</span>
    <span class="marquee-item">Master Data Configuration</span>
    <span class="marquee-item">Import Operations</span>
    <span class="marquee-item">Mumbai · Remote Global</span>
  </div>
</div>

<!-- ABOUT -->
<section class="section" id="about">
  <div class="about-grid">
    <div>
      <div class="eyebrow">About me</div>
      <h2 class="section-h">ERP consultant.<br>Supply chain veteran.</h2>
      <div class="about-body">
        <p>I'm <strong>Yadnesh Naresh Patil</strong>, a Dynamics 365 F&amp;O Functional Consultant currently at <strong>Key Dynamics Solutions Pvt. Ltd.</strong> in Delhi. What sets me apart from most ERP consultants is a genuine 6+ year background in live supply chain and logistics operations before moving into consulting.</p>
        <p>I spent years working at <strong>BDP UGL Global Logistics</strong> and <strong>CMA-CGM</strong> — handling real import clearance, bonded cargo, detention &amp; demurrage, and cross-functional ERP workflows. That operational depth means I don't just map processes in theory — I've lived them.</p>
        <p>Today I bring that ground-level experience into D365 projects, helping clients bridge the gap between what the system can do and what their business actually needs across <strong>SCM, Procurement, and Inventory</strong>.</p>
      </div>
      <div class="about-stats">
        <div class="astat"><span class="astat-num">7+</span><span class="astat-label">Years total experience</span></div>
        <div class="astat"><span class="astat-num">3</span><span class="astat-label">Industries served</span></div>
        <div class="astat"><span class="astat-num">D365</span><span class="astat-label">F&amp;O &amp; AX 2012</span></div>
        <div class="astat"><span class="astat-num">Global</span><span class="astat-label">Remote ready</span></div>
      </div>
    </div>
    <div class="edu-block">
      <h3>Education</h3>
      <div class="edu-item">
        <div class="edu-deg">Post Graduate Diploma in Supply Chain Management</div>
        <div class="edu-school">Welingkar Institute of Management Development &amp; Research, University of Mumbai</div>
        <div class="edu-year">2016 – 2018</div>
      </div>
      <div class="edu-item">
        <div class="edu-deg">Master of Commerce – Business Management</div>
        <div class="edu-school">M.L. Dahanukar College of Commerce, University of Mumbai</div>
        <div class="edu-year">2016 – 2018</div>
      </div>
      <div class="edu-item">
        <div class="edu-deg">Bachelor of Commerce</div>
        <div class="edu-school">M.L. Dahanukar College of Commerce, University of Mumbai</div>
        <div class="edu-year">2014 – 2016</div>
      </div>
      <div style="margin-top:1.5rem; padding-top:1.2rem; border-top:1px solid var(--rule);">
        <div style="font-size:0.75rem; color:var(--muted); margin-bottom:0.5rem; font-weight:500;">Languages</div>
        <div style="display:flex; gap:6px; flex-wrap:wrap;">
          <span class="htag" style="font-size:0.7rem;">Marathi</span>
          <span class="htag" style="font-size:0.7rem;">Hindi</span>
          <span class="htag" style="font-size:0.7rem;">English</span>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- EXPERIENCE -->
<div class="section-full exp-wrap" id="experience">
  <div class="section-full-inner exp-inner">
    <div class="eyebrow">Work experience</div>
    <h2 class="section-h">Where I've worked</h2>
    <p class="section-desc">From global shipping operations to Microsoft ERP consulting — a career built on real supply chain experience.</p>
    <div class="timeline">

      <div class="tl-item">
        <div class="tl-left">
          <div class="tl-period">Feb 2025 – Present</div>
          <div class="tl-company">Key Dynamics Solutions Pvt. Ltd.</div>
          <div class="tl-loc">Delhi, India</div>
        </div>
        <div class="tl-right">
          <div class="tl-role">Functional Consultant – Finance &amp; Operations</div>
          <div class="tl-desc">Providing functional consulting on D365 F&amp;O across SCM, Procurement, and Inventory modules. Supporting fit-gap analysis, requirement documentation, UAT scripts, and master data configurations. Configuring procurement flows including vendors, purchase orders, product receipts, and invoice matching. Interacting directly with clients to map logistics processes to D365 standard functionalities. Also gained exposure to AX 2012 for legacy system comparison.</div>
          <div class="tl-pills">
            <span class="tl-pill">D365 F&amp;O</span>
            <span class="tl-pill">AX 2012</span>
            <span class="tl-pill">Procurement</span>
            <span class="tl-pill">SCM</span>
            <span class="tl-pill">Fit-Gap Analysis</span>
            <span class="tl-pill">UAT</span>
            <span class="tl-pill">Master Data</span>
          </div>
        </div>
      </div>

      <div class="tl-item">
        <div class="tl-left">
          <div class="tl-period">Jul 2019 – Feb 2025</div>
          <div class="tl-company">BDP UGL Global Logistics (India) Pvt. Ltd.</div>
          <div class="tl-loc">Mumbai, India</div>
        </div>
        <div class="tl-right">
          <div class="tl-role">Senior Executive – Import Operations (CHB)</div>
          <div class="tl-desc">Coordinated end-to-end import clearance activities using company ERP systems. Managed DPD shipments, bonded cargo, and factory de-stuff operations aligned with ERP data flows. Handled shipping line communications, invoice validations, and document submissions. Regularly collaborated cross-functionally to ensure invoice matching, delivery order processing, and container release were accurately logged. Supported junior team members and vendors on system usage and compliance.</div>
          <div class="tl-pills">
            <span class="tl-pill">Import Clearance</span>
            <span class="tl-pill">Bonded Cargo</span>
            <span class="tl-pill">ERP Operations</span>
            <span class="tl-pill">Invoice Matching</span>
            <span class="tl-pill">CHB</span>
          </div>
        </div>
      </div>

      <div class="tl-item">
        <div class="tl-left">
          <div class="tl-period">Dec 2016 – Jun 2019</div>
          <div class="tl-company">CMA-CGM Shared Services (India) Pvt. Ltd.</div>
          <div class="tl-loc">Mumbai, India</div>
        </div>
        <div class="tl-right">
          <div class="tl-role">Senior Executive – Operations (DDSM)</div>
          <div class="tl-desc">Managed global Detention, Demurrage &amp; Storage Monitoring operations via internal ERP tools, serving European and Latin American markets. Delivered SOPs, SLA matrices, and internal reports for key stakeholders. Managed dispute resolutions, process transitions, and internal audits. Leveraged process automation tools for workflow tracking, performance KPIs, and service quality audits.</div>
          <div class="tl-pills">
            <span class="tl-pill">DDSM</span>
            <span class="tl-pill">Global Operations</span>
            <span class="tl-pill">SLA Management</span>
            <span class="tl-pill">Process Automation</span>
            <span class="tl-pill">SOPs</span>
          </div>
        </div>
      </div>

    </div>
  </div>
</div>

<!-- SKILLS -->
<section class="section" id="skills">
  <div class="eyebrow">Expertise</div>
  <h2 class="section-h">What I bring to every project</h2>
  <p class="section-desc">Functional depth across D365 modules, backed by hands-on operational experience in logistics and supply chain.</p>
  <div class="skills-grid">
    <div class="skill-card">
      <div class="sk-icon blue">⚙️</div>
      <h3>D365 F&amp;O – Core Modules</h3>
      <p>Functional configuration and support across SCM, Procurement, Inventory, and Finance modules within D365 F&amp;O.</p>
      <div class="sk-tags">
        <span class="sk-tag">SCM</span><span class="sk-tag">Procurement</span>
        <span class="sk-tag">Inventory</span><span class="sk-tag">Finance</span>
        <span class="sk-tag">AX 2012</span>
      </div>
    </div>
    <div class="skill-card">
      <div class="sk-icon teal">🔄</div>
      <h3>Implementation &amp; Migrations</h3>
      <p>Supporting full project lifecycle — from fit-gap through UAT scripts, data migration validation, and go-live cutover.</p>
      <div class="sk-tags">
        <span class="sk-tag">Fit-Gap Analysis</span><span class="sk-tag">UAT</span>
        <span class="sk-tag">Data Migration</span><span class="sk-tag">Cutover</span>
        <span class="sk-tag">AX → D365</span>
      </div>
    </div>
    <div class="skill-card">
      <div class="sk-icon amber">📋</div>
      <h3>Functional Documentation</h3>
      <p>Requirement gathering, BRD/FRD documentation, process mapping, and master data configuration to ensure alignment between business and system.</p>
      <div class="sk-tags">
        <span class="sk-tag">BRD / FRD</span><span class="sk-tag">Process Mapping</span>
        <span class="sk-tag">Master Data</span><span class="sk-tag">Configuration</span>
      </div>
    </div>
    <div class="skill-card">
      <div class="sk-icon blue">🛠️</div>
      <h3>Support &amp; Enhancement</h3>
      <p>Post go-live functional support, SLA-driven ticket resolution, change requests, and end-user training.</p>
      <div class="sk-tags">
        <span class="sk-tag">Ticket Support</span><span class="sk-tag">SLA Adherence</span>
        <span class="sk-tag">Issue Resolution</span><span class="sk-tag">User Training</span>
      </div>
    </div>
    <div class="skill-card">
      <div class="sk-icon teal">🚢</div>
      <h3>Supply Chain &amp; Logistics</h3>
      <p>6+ years of hands-on SCM experience in import operations, bonded cargo, detention &amp; demurrage, and global freight ERP workflows.</p>
      <div class="sk-tags">
        <span class="sk-tag">Import Ops</span><span class="sk-tag">CHB</span>
        <span class="sk-tag">DDSM</span><span class="sk-tag">Freight ERP</span>
      </div>
    </div>
    <div class="skill-card">
      <div class="sk-icon amber">🏭</div>
      <h3>Industries Served</h3>
      <p>Worked across diverse industries — giving a broad view of how different businesses leverage ERP to drive efficiency.</p>
      <div class="sk-tags">
        <span class="sk-tag">Manufacturing</span><span class="sk-tag">Retail &amp; Distribution</span>
        <span class="sk-tag">Professional Services</span><span class="sk-tag">Logistics</span>
      </div>
    </div>
  </div>
</section>

<!-- CERTIFICATIONS -->
<div class="section-full certs-bg" id="certifications">
  <div class="section-full-inner">
    <div class="eyebrow">Certifications</div>
    <h2 class="section-h">Microsoft credentials</h2>
    <p class="section-desc">Staying current with the Microsoft Dynamics 365 certification pathway.</p>
    <div class="certs-grid">
      <div class="cert-card">
        <div class="cert-icon done">MB<br>300</div>
        <div>
          <div class="cert-title">MB-300: Microsoft Dynamics 365 Core</div>
          <div class="cert-sub">Core Finance &amp; Operations certification — foundation for all D365 F&amp;O functional consultants</div>
          <span class="cert-badge done">Completed</span>
        </div>
      </div>
      <div class="cert-card">
        <div class="cert-icon planned">MB<br>330</div>
        <div>
          <div class="cert-title">MB-330: Supply Chain Management</div>
          <div class="cert-sub">Microsoft Dynamics 365 Supply Chain Management Functional Consultant Associate — currently in progress</div>
          <span class="cert-badge planned">In progress</span>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- ARTICLES -->
<section class="section" id="articles">
  <div class="eyebrow">Writing</div>
  <h2 class="section-h">Weekly LinkedIn articles</h2>
  <p class="section-desc">Sharing practical D365 insights, ERP consulting lessons, and supply chain perspectives every week on LinkedIn.</p>
  <div class="articles-grid">
    <a href="https://www.linkedin.com/in/yadneshnareshpatil-2696/" target="_blank" class="article-card">
      <div class="art-cat">D365 F&amp;O · Troubleshooting</div>
      <div class="art-title">Why "Item Not Found" Errors Occur in PR Lines Even When Item Exists in D365 F&amp;O</div>
      <div class="art-meta">Published on LinkedIn</div>
      <div class="art-arrow">↗</div>
    </a>
    <a href="https://www.linkedin.com/in/yadneshnareshpatil-2696/" target="_blank" class="article-card">
      <div class="art-cat">ERP Consulting</div>
      <div class="art-title">What does a D365 Functional Consultant actually do day-to-day?</div>
      <div class="art-meta">Weekly series on LinkedIn</div>
      <div class="art-arrow">↗</div>
    </a>
    <a href="https://www.linkedin.com/in/yadneshnareshpatil-2696/" target="_blank" class="article-card">
      <div class="art-cat">Supply Chain</div>
      <div class="art-title">From Logistics Operations to ERP Consulting — how my SCM background shapes my consulting approach</div>
      <div class="art-meta">Weekly series on LinkedIn</div>
      <div class="art-arrow">↗</div>
    </a>
  </div>
  <a href="https://www.linkedin.com/in/yadneshnareshpatil-2696/" target="_blank" class="articles-li-cta">
    Read all articles on LinkedIn →
  </a>
</section>

<!-- CONTACT -->
<div class="section-full contact-bg" id="contact">
  <div class="section-full-inner">
    <div class="contact-inner">
      <div class="eyebrow">Contact</div>
      <h2 class="section-h">Let's work together</h2>
      <p class="section-desc">Open to remote consulting engagements, freelance projects, and professional conversations around D365 and ERP. Based in Mumbai, available globally.</p>
      <div class="contact-links">
        <a href="https://www.linkedin.com/in/yadneshnareshpatil-2696/" target="_blank" class="contact-link">
          <svg viewBox="0 0 24 24"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 01-2.063-2.065 2.064 2.064 0 112.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
          LinkedIn
        </a>
        <a href="mailto:yadnesh@yadneshpatil.in" class="contact-link">
          <svg viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/></svg>
          yadnesh@yadneshpatil.in
        </a>
        <a href="tel:+918976191640" class="contact-link">
          <svg viewBox="0 0 24 24"><path d="M6.62 10.79c1.44 2.83 3.76 5.14 6.59 6.59l2.2-2.2c.27-.27.67-.36 1.02-.24 1.12.37 2.33.57 3.57.57.55 0 1 .45 1 1V20c0 .55-.45 1-1 1-9.39 0-17-7.61-17-17 0-.55.45-1 1-1h3.5c.55 0 1 .45 1 1 0 1.25.2 2.45.57 3.57.11.35.03.74-.25 1.02l-2.2 2.2z"/></svg>
          +91 89761 91640
        </a>
        <a href="https://yadneshpatil.in" class="contact-link">
          <svg viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 17.93c-3.95-.49-7-3.85-7-7.93 0-.62.08-1.21.21-1.79L9 15v1c0 1.1.9 2 2 2v1.93zm6.9-2.54c-.26-.81-1-1.39-1.9-1.39h-1v-3c0-.55-.45-1-1-1H8v-2h2c.55 0 1-.45 1-1V7h2c1.1 0 2-.9 2-2v-.41c2.93 1.19 5 4.06 5 7.41 0 2.08-.8 3.97-2.1 5.39z"/></svg>
          yadneshpatil.in
        </a>
      </div>
    </div>
  </div>
</div>

<!-- FOOTER -->
<footer>
  <div class="footer-logo">YP.</div>
  <div class="footer-copy">© 2026 Yadnesh Naresh Patil · Mumbai, India</div>
  <div class="footer-domain">yadneshpatil.in</div>
</footer>

</body>
</html>
