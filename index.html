<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>CoreAccess — Semantic Intelligence</title>
<link rel="preconnect" href="https://fonts.googleapis.com"/>
<link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;600;700;800&family=DM+Mono:wght@300;400;500&display=swap" rel="stylesheet"/>
<style>
:root {
  --neural: #D4FF00;
  --neural-dim: #A8CC00;
  --neural-glow: rgba(212,255,0,0.15);
  --bg: #060608;
  --bg2: #0C0C10;
  --bg3: #111118;
  --surface: #14141C;
  --border: rgba(212,255,0,0.12);
  --border2: rgba(255,255,255,0.06);
  --text: #F0F0F0;
  --muted: #666680;
  --muted2: #3A3A4A;
}

*{margin:0;padding:0;box-sizing:border-box;}

html{scroll-behavior:smooth;}

body{
  background:var(--bg);
  color:var(--text);
  font-family:'DM Mono',monospace;
  font-size:15px;
  line-height:1.7;
  overflow-x:hidden;
  cursor:none;
}

/* ── CURSEUR NEURAL ─────────────────────────────────────────────── */
.cursor{
  position:fixed;width:8px;height:8px;
  background:var(--neural);border-radius:50%;
  pointer-events:none;z-index:9999;
  transform:translate(-50%,-50%);
  transition:transform 0.1s ease;
  box-shadow:0 0 12px var(--neural),0 0 24px rgba(212,255,0,0.4);
}
.cursor-ring{
  position:fixed;width:32px;height:32px;
  border:1px solid rgba(212,255,0,0.4);border-radius:50%;
  pointer-events:none;z-index:9998;
  transform:translate(-50%,-50%);
  transition:all 0.15s ease;
}

/* ── CANVAS NEURAL BACKGROUND ───────────────────────────────────── */
#neural-canvas{
  position:fixed;top:0;left:0;
  width:100%;height:100%;
  z-index:0;opacity:0.35;
  pointer-events:none;
}

/* ── NAV ────────────────────────────────────────────────────────── */
nav{
  position:fixed;top:0;left:0;right:0;
  z-index:100;
  padding:0 48px;
  height:64px;
  display:flex;align-items:center;justify-content:space-between;
  background:rgba(6,6,8,0.85);
  backdrop-filter:blur(24px);
  border-bottom:1px solid var(--border2);
}

.nav-logo{
  font-family:'Syne',sans-serif;
  font-weight:800;font-size:18px;
  letter-spacing:-0.5px;
  color:var(--text);
  text-decoration:none;
  display:flex;align-items:center;gap:10px;
}

.nav-logo span{
  color:var(--neural);
  font-size:22px;
  animation:pulse-dot 2s ease-in-out infinite;
}

@keyframes pulse-dot{
  0%,100%{opacity:1;text-shadow:0 0 8px var(--neural);}
  50%{opacity:0.5;text-shadow:none;}
}

.nav-links{
  display:flex;gap:0;
  list-style:none;
}

.nav-links a{
  display:block;
  padding:8px 20px;
  font-size:12px;
  letter-spacing:2px;
  text-transform:uppercase;
  text-decoration:none;
  color:var(--muted);
  transition:color 0.2s;
  position:relative;
}

.nav-links a::after{
  content:'';
  position:absolute;bottom:-1px;left:20px;right:20px;
  height:1px;background:var(--neural);
  transform:scaleX(0);
  transition:transform 0.2s ease;
}

.nav-links a:hover,
.nav-links a.active{
  color:var(--neural);
}

.nav-links a:hover::after,
.nav-links a.active::after{
  transform:scaleX(1);
}

/* ── SECTIONS ───────────────────────────────────────────────────── */
.page{
  min-height:100vh;
  display:none;
  position:relative;
  z-index:1;
}

.page.active{display:block;}

/* ── HERO — SYNAPSO ─────────────────────────────────────────────── */
#page-synapso{
  padding-top:64px;
}

.hero{
  min-height:100vh;
  display:flex;flex-direction:column;
  justify-content:center;
  padding:0 48px;
  max-width:1200px;
  margin:0 auto;
  position:relative;
}

.hero-eyebrow{
  font-size:11px;letter-spacing:4px;
  text-transform:uppercase;
  color:var(--neural);
  margin-bottom:24px;
  display:flex;align-items:center;gap:12px;
}

.hero-eyebrow::before{
  content:'';
  display:inline-block;
  width:32px;height:1px;
  background:var(--neural);
}

.hero-title{
  font-family:'Syne',sans-serif;
  font-size:clamp(48px,8vw,96px);
  font-weight:800;
  line-height:0.95;
  letter-spacing:-3px;
  margin-bottom:32px;
  color:#fff;
}

.hero-title em{
  font-style:normal;
  color:var(--neural);
  position:relative;
}

.hero-title em::after{
  content:'';
  position:absolute;bottom:-4px;left:0;right:0;
  height:2px;background:var(--neural);
  box-shadow:0 0 16px var(--neural);
}

.hero-sub{
  font-size:16px;
  color:var(--muted);
  max-width:560px;
  margin-bottom:56px;
  line-height:1.8;
}

.hero-cta{
  display:inline-flex;align-items:center;gap:12px;
  background:var(--neural);
  color:#000;
  padding:14px 28px;
  font-family:'Syne',sans-serif;
  font-weight:700;
  font-size:13px;
  letter-spacing:1px;
  text-transform:uppercase;
  text-decoration:none;
  border:none;cursor:none;
  transition:all 0.2s ease;
}

.hero-cta:hover{
  background:#fff;
  transform:translateX(4px);
}

.hero-cta-arrow{
  transition:transform 0.2s;
}

.hero-cta:hover .hero-cta-arrow{
  transform:translateX(4px);
}

/* Floating stats */
.hero-stats{
  position:absolute;right:48px;top:50%;
  transform:translateY(-50%);
  display:flex;flex-direction:column;gap:32px;
}

.stat{
  text-align:right;
}

.stat-num{
  font-family:'Syne',sans-serif;
  font-size:36px;font-weight:800;
  color:var(--neural);
  line-height:1;
}

.stat-label{
  font-size:10px;
  letter-spacing:2px;
  text-transform:uppercase;
  color:var(--muted);
  margin-top:4px;
}

/* ── DEMO SECTION ───────────────────────────────────────────────── */
.demo-section{
  padding:120px 48px;
  max-width:1200px;
  margin:0 auto;
}

.section-label{
  font-size:11px;letter-spacing:4px;
  text-transform:uppercase;
  color:var(--neural);
  margin-bottom:16px;
  display:flex;align-items:center;gap:12px;
}

.section-label::before{
  content:'';width:24px;height:1px;background:var(--neural);
}

.section-title{
  font-family:'Syne',sans-serif;
  font-size:clamp(32px,4vw,52px);
  font-weight:800;
  letter-spacing:-2px;
  color:#fff;
  margin-bottom:64px;
  line-height:1.1;
}

/* Demo cards */
.demo-grid{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:2px;
  margin-bottom:80px;
}

.demo-card{
  background:var(--surface);
  padding:32px;
  position:relative;
  overflow:hidden;
  transition:background 0.3s;
}

.demo-card::before{
  content:'';
  position:absolute;top:0;left:0;right:0;
  height:1px;
  background:linear-gradient(90deg,transparent,var(--neural),transparent);
  opacity:0;
  transition:opacity 0.3s;
}

.demo-card:hover{background:var(--bg3);}
.demo-card:hover::before{opacity:1;}

.demo-mode{
  font-size:10px;letter-spacing:3px;
  text-transform:uppercase;
  color:var(--neural);
  margin-bottom:16px;
}

.demo-before{
  font-size:13px;
  color:var(--muted);
  margin-bottom:12px;
  line-height:1.6;
  font-style:italic;
}

.demo-after{
  font-size:14px;
  color:var(--text);
  line-height:1.6;
}

.demo-after mark{
  background:transparent;
  color:var(--neural);
  font-weight:500;
  text-shadow:0 0 8px rgba(212,255,0,0.4);
}

.demo-arrow{
  color:var(--muted2);
  font-size:11px;
  margin:8px 0;
}

/* Verticales */
.vertical-grid{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:16px;
}

.vertical-item{
  border:1px solid var(--border2);
  padding:24px;
  position:relative;
  transition:border-color 0.2s,background 0.2s;
}

.vertical-item:hover{
  border-color:var(--border);
  background:var(--neural-glow);
}

.vertical-num{
  font-family:'Syne',sans-serif;
  font-size:48px;font-weight:800;
  color:var(--muted2);
  line-height:1;
  margin-bottom:12px;
}

.vertical-name{
  font-family:'Syne',sans-serif;
  font-size:16px;font-weight:700;
  color:#fff;
  margin-bottom:6px;
}

.vertical-desc{
  font-size:12px;
  color:var(--muted);
  line-height:1.6;
}

/* ── TARIFS ─────────────────────────────────────────────────────── */
#page-tarifs{padding-top:64px;}

.tarifs-hero{
  padding:120px 48px 80px;
  max-width:1200px;margin:0 auto;
}

.pricing-grid{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:2px;
  max-width:1200px;
  margin:0 auto 80px;
  padding:0 48px;
}

.pricing-card{
  background:var(--surface);
  padding:48px 36px;
  position:relative;
  overflow:hidden;
}

.pricing-card.featured{
  background:var(--bg3);
  border:1px solid var(--neural);
}

.pricing-card.featured::before{
  content:'RECOMMANDÉ';
  position:absolute;top:20px;right:20px;
  font-size:9px;letter-spacing:3px;
  background:var(--neural);
  color:#000;
  padding:4px 10px;
  font-weight:700;
}

.pricing-tier{
  font-size:11px;letter-spacing:3px;
  text-transform:uppercase;
  color:var(--neural);
  margin-bottom:16px;
}

.pricing-name{
  font-family:'Syne',sans-serif;
  font-size:28px;font-weight:800;
  color:#fff;
  margin-bottom:8px;
  letter-spacing:-1px;
}

.pricing-price{
  font-family:'Syne',sans-serif;
  font-size:52px;font-weight:800;
  color:var(--neural);
  line-height:1;
  margin:24px 0 4px;
  letter-spacing:-2px;
}

.pricing-price span{
  font-size:18px;
  color:var(--muted);
  font-weight:400;
  letter-spacing:0;
}

.pricing-note{
  font-size:11px;
  color:var(--muted);
  margin-bottom:32px;
}

.pricing-divider{
  height:1px;
  background:var(--border2);
  margin:32px 0;
}

.pricing-features{
  list-style:none;
  display:flex;flex-direction:column;gap:14px;
  margin-bottom:40px;
}

.pricing-features li{
  font-size:13px;
  color:var(--muted);
  display:flex;align-items:flex-start;gap:10px;
  line-height:1.5;
}

.pricing-features li::before{
  content:'→';
  color:var(--neural);
  flex-shrink:0;
  font-size:11px;
  margin-top:2px;
}

.pricing-cta{
  display:block;
  text-align:center;
  padding:14px;
  border:1px solid var(--border);
  color:var(--neural);
  text-decoration:none;
  font-size:12px;
  letter-spacing:2px;
  text-transform:uppercase;
  transition:all 0.2s;
  cursor:none;
}

.pricing-cta:hover,
.pricing-card.featured .pricing-cta{
  background:var(--neural);
  color:#000;
  border-color:var(--neural);
}

/* Revenue share section */
.revenue-section{
  padding:80px 48px;
  max-width:1200px;margin:0 auto;
}

.revenue-grid{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:2px;
}

.revenue-item{
  background:var(--surface);
  padding:40px;
}

.revenue-label{
  font-size:11px;letter-spacing:3px;
  text-transform:uppercase;
  color:var(--neural);
  margin-bottom:12px;
}

.revenue-title{
  font-family:'Syne',sans-serif;
  font-size:22px;font-weight:700;
  color:#fff;
  margin-bottom:8px;
  letter-spacing:-0.5px;
}

.revenue-desc{
  font-size:13px;
  color:var(--muted);
  line-height:1.7;
}

/* ── CONTACT ────────────────────────────────────────────────────── */
#page-contact{padding-top:64px;}

.contact-wrap{
  padding:120px 48px;
  max-width:1200px;margin:0 auto;
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:80px;
  align-items:start;
}

.contact-info{}

.contact-title{
  font-family:'Syne',sans-serif;
  font-size:clamp(36px,5vw,64px);
  font-weight:800;
  letter-spacing:-2px;
  color:#fff;
  line-height:1.05;
  margin-bottom:32px;
}

.contact-title em{
  font-style:normal;color:var(--neural);
}

.contact-desc{
  font-size:14px;
  color:var(--muted);
  line-height:1.8;
  margin-bottom:48px;
}

.contact-methods{
  display:flex;flex-direction:column;gap:20px;
}

.contact-method{
  display:flex;align-items:center;gap:16px;
  padding:20px 24px;
  border:1px solid var(--border2);
  text-decoration:none;
  color:var(--text);
  transition:border-color 0.2s,background 0.2s;
}

.contact-method:hover{
  border-color:var(--border);
  background:var(--neural-glow);
}

.contact-method-icon{
  font-size:11px;letter-spacing:2px;
  color:var(--neural);
  width:60px;flex-shrink:0;
}

.contact-method-label{
  font-size:13px;
  color:var(--muted);
  font-size:12px;
  letter-spacing:1px;
}

.contact-method-value{
  font-family:'Syne',sans-serif;
  font-size:15px;font-weight:600;
  color:#fff;
}

/* Form */
.contact-form{
  display:flex;flex-direction:column;gap:16px;
}

.form-group{
  display:flex;flex-direction:column;gap:8px;
}

.form-label{
  font-size:10px;letter-spacing:3px;
  text-transform:uppercase;
  color:var(--muted);
}

.form-input,
.form-textarea,
.form-select{
  background:var(--surface);
  border:1px solid var(--border2);
  color:var(--text);
  padding:14px 18px;
  font-family:'DM Mono',monospace;
  font-size:14px;
  outline:none;
  transition:border-color 0.2s;
  width:100%;
  cursor:none;
}

.form-input:focus,
.form-textarea:focus,
.form-select:focus{
  border-color:var(--neural);
}

.form-textarea{resize:vertical;min-height:120px;}

.form-select option{background:var(--bg);}

.form-submit{
  background:var(--neural);
  color:#000;
  border:none;
  padding:16px 32px;
  font-family:'Syne',sans-serif;
  font-weight:700;
  font-size:13px;
  letter-spacing:2px;
  text-transform:uppercase;
  cursor:none;
  transition:all 0.2s;
  align-self:flex-start;
}

.form-submit:hover{
  background:#fff;
  transform:translateX(4px);
}

/* ── QUI SOMMES NOUS ────────────────────────────────────────────── */
#page-about{padding-top:64px;}

.about-hero{
  padding:120px 48px 80px;
  max-width:1200px;margin:0 auto;
}

.about-manifesto{
  font-family:'Syne',sans-serif;
  font-size:clamp(24px,3.5vw,42px);
  font-weight:700;
  letter-spacing:-1px;
  line-height:1.3;
  color:#fff;
  max-width:800px;
  margin-bottom:80px;
}

.about-manifesto em{
  font-style:normal;color:var(--neural);
}

.about-grid{
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:2px;
  margin-bottom:80px;
}

.about-block{
  background:var(--surface);
  padding:48px;
}

.about-block-label{
  font-size:10px;letter-spacing:4px;
  text-transform:uppercase;
  color:var(--neural);
  margin-bottom:20px;
}

.about-block-title{
  font-family:'Syne',sans-serif;
  font-size:24px;font-weight:700;
  color:#fff;
  margin-bottom:16px;
  letter-spacing:-0.5px;
}

.about-block-text{
  font-size:13px;
  color:var(--muted);
  line-height:1.8;
}

/* Tech stack */
.tech-section{
  padding:80px 48px;
  max-width:1200px;margin:0 auto;
}

.tech-row{
  display:flex;
  border-top:1px solid var(--border2);
}

.tech-row:last-child{border-bottom:1px solid var(--border2);}

.tech-num{
  width:80px;flex-shrink:0;
  padding:28px 0;
  font-family:'Syne',sans-serif;
  font-size:12px;
  color:var(--muted2);
  letter-spacing:2px;
}

.tech-name{
  flex:1;
  padding:28px 32px;
  font-family:'Syne',sans-serif;
  font-size:18px;font-weight:700;
  color:#fff;
  letter-spacing:-0.5px;
  border-left:1px solid var(--border2);
}

.tech-desc{
  flex:2;
  padding:28px 32px;
  font-size:13px;
  color:var(--muted);
  line-height:1.7;
  border-left:1px solid var(--border2);
}

/* ── FOOTER ─────────────────────────────────────────────────────── */
footer{
  border-top:1px solid var(--border2);
  padding:40px 48px;
  display:flex;
  justify-content:space-between;
  align-items:center;
  position:relative;z-index:1;
}

.footer-logo{
  font-family:'Syne',sans-serif;
  font-weight:800;font-size:14px;
  color:var(--text);
}

.footer-logo span{color:var(--neural);}

.footer-note{
  font-size:11px;
  color:var(--muted2);
  letter-spacing:1px;
}

.footer-patent{
  font-size:11px;
  color:var(--muted2);
  letter-spacing:1px;
  text-align:right;
}

/* ── RESPONSIVE ─────────────────────────────────────────────────── */
@media(max-width:768px){
  nav{padding:0 24px;}
  .nav-links{display:none;}
  .hero,.demo-section,.tarifs-hero,.contact-wrap,
  .revenue-section,.about-hero,.tech-section{
    padding-left:24px;padding-right:24px;
  }
  .hero-stats{display:none;}
  .demo-grid,.vertical-grid,.pricing-grid,
  .revenue-grid,.about-grid{
    grid-template-columns:1fr;
  }
  .contact-wrap{grid-template-columns:1fr;gap:48px;}
  .hero-title{font-size:42px;letter-spacing:-2px;}
  footer{flex-direction:column;gap:16px;text-align:center;}
}

/* ── ANIMATIONS ─────────────────────────────────────────────────── */
@keyframes fadeUp{
  from{opacity:0;transform:translateY(24px);}
  to{opacity:1;transform:translateY(0);}
}

.page.active .hero-eyebrow{animation:fadeUp 0.6s ease both;}
.page.active .hero-title{animation:fadeUp 0.6s 0.1s ease both;}
.page.active .hero-sub{animation:fadeUp 0.6s 0.2s ease both;}
.page.active .hero-cta{animation:fadeUp 0.6s 0.3s ease both;}
.page.active .hero-stats{animation:fadeUp 0.6s 0.2s ease both;}

/* Mobile nav */
.mobile-nav{
  display:none;
  position:fixed;bottom:0;left:0;right:0;
  background:rgba(6,6,8,0.95);
  backdrop-filter:blur(20px);
  border-top:1px solid var(--border2);
  z-index:100;
  padding:12px 0 20px;
}

.mobile-nav-links{
  display:flex;justify-content:space-around;
  list-style:none;
}

.mobile-nav-links a{
  display:flex;flex-direction:column;align-items:center;gap:4px;
  text-decoration:none;
  color:var(--muted);
  font-size:9px;letter-spacing:2px;
  text-transform:uppercase;
  transition:color 0.2s;
  padding:8px 16px;
}

.mobile-nav-links a.active,
.mobile-nav-links a:hover{color:var(--neural);}

.mobile-nav-dot{
  width:4px;height:4px;border-radius:50%;
  background:var(--muted2);
  transition:background 0.2s;
}

.mobile-nav-links a.active .mobile-nav-dot{
  background:var(--neural);
  box-shadow:0 0 6px var(--neural);
}

@media(max-width:768px){
  .mobile-nav{display:block;}
  body{padding-bottom:80px;}
}
</style>
</head>
<body>

<div class="cursor" id="cursor"></div>
<div class="cursor-ring" id="cursor-ring"></div>

<canvas id="neural-canvas"></canvas>

<!-- NAV DESKTOP -->
<nav>
  <a href="#" class="nav-logo" onclick="showPage('synapso');return false;">
    <span>◈</span> CoreAccess
  </a>
  <ul class="nav-links">
    <li><a href="#" class="active" data-page="synapso" onclick="showPage('synapso');return false;">Synapso</a></li>
    <li><a href="#" data-page="tarifs" onclick="showPage('tarifs');return false;">Tarifs</a></li>
    <li><a href="#" data-page="contact" onclick="showPage('contact');return false;">Contact</a></li>
    <li><a href="#" data-page="about" onclick="showPage('about');return false;">À propos</a></li>
  </ul>
</nav>

<!-- NAV MOBILE -->
<nav class="mobile-nav">
  <ul class="mobile-nav-links">
    <li><a href="#" class="active" data-page="synapso" onclick="showPage('synapso');return false;"><div class="mobile-nav-dot"></div>Synapso</a></li>
    <li><a href="#" data-page="tarifs" onclick="showPage('tarifs');return false;"><div class="mobile-nav-dot"></div>Tarifs</a></li>
    <li><a href="#" data-page="contact" onclick="showPage('contact');return false;"><div class="mobile-nav-dot"></div>Contact</a></li>
    <li><a href="#" data-page="about" onclick="showPage('about');return false;"><div class="mobile-nav-dot"></div>À propos</a></li>
  </ul>
</nav>


<!-- ════════════════════════════ PAGE SYNAPSO ════════════════════ -->
<div class="page active" id="page-synapso">

  <section class="hero">
    <div class="hero-eyebrow">CoreAccess · Produit 01</div>
    <h1 class="hero-title">
      La publicité<br>
      qui <em>pense</em><br>
      le langage.
    </h1>
    <p class="hero-sub">
      Synapso insère des marques dans du contenu naturel par correspondance vectorielle sémantique. Invisible. Précis. Breveté.
    </p>
    <a href="#" class="hero-cta" onclick="showPage('tarifs');return false;">
      Voir les offres <span class="hero-cta-arrow">→</span>
    </a>

    <div class="hero-stats">
      <div class="stat">
        <div class="stat-num">$217B</div>
        <div class="stat-label">Marché 2024</div>
      </div>
      <div class="stat">
        <div class="stat-num">9</div>
        <div class="stat-label">Verticales</div>
      </div>
      <div class="stat">
        <div class="stat-num">30+</div>
        <div class="stat-label">Marques vault</div>
      </div>
    </div>
  </section>

  <div class="demo-section">
    <div class="section-label">Démonstration live</div>
    <h2 class="section-title">Le moteur en action.</h2>

    <div class="demo-grid">
      <div class="demo-card">
        <div class="demo-mode">Lyrics · EN</div>
        <div class="demo-before">"Going to the shop imma buy my bag alone"</div>
        <div class="demo-arrow">↓ Synapso</div>
        <div class="demo-after">"Going to <mark>Louis Vuitton</mark> imma buy my <mark>Neverfull</mark> alone"</div>
      </div>
      <div class="demo-card">
        <div class="demo-mode">GPS · FR</div>
        <div class="demo-before">"Tournez à gauche au prochain café"</div>
        <div class="demo-arrow">↓ Synapso</div>
        <div class="demo-after">"Tournez à gauche au prochain <mark>Starbucks</mark>"</div>
      </div>
      <div class="demo-card">
        <div class="demo-mode">Subtitle · EN</div>
        <div class="demo-before">[drinks from a can]</div>
        <div class="demo-arrow">↓ Synapso</div>
        <div class="demo-after">[drinks from a <mark>Coca-Cola</mark> can]</div>
      </div>
      <div class="demo-card">
        <div class="demo-mode">Éducation · FR</div>
        <div class="demo-before">"Je bois une boisson fraîche après mon sport"</div>
        <div class="demo-arrow">↓ Synapso</div>
        <div class="demo-after">"Je bois une <mark>Evian</mark> fraîche après mon sport"</div>
      </div>
      <div class="demo-card">
        <div class="demo-mode">Gaming · EN</div>
        <div class="demo-before">"Grab a drink before the next round."</div>
        <div class="demo-arrow">↓ Synapso</div>
        <div class="demo-after">"Grab a <mark>Red Bull</mark> before the next round."</div>
      </div>
      <div class="demo-card">
        <div class="demo-mode">Prose · FR</div>
        <div class="demo-before">"Elle portait une montre élégante"</div>
        <div class="demo-arrow">↓ Synapso</div>
        <div class="demo-after">"Elle portait une <mark>Rolex</mark> élégante"</div>
      </div>
    </div>

    <div class="section-label">9 marchés adressables</div>
    <h2 class="section-title">Un moteur.<br>Neuf verticales.</h2>

    <div class="vertical-grid">
      <div class="vertical-item">
        <div class="vertical-num">01</div>
        <div class="vertical-name">Musique streaming</div>
        <div class="vertical-desc">Paroles affichées en temps réel. Spotify, Deezer, Apple Music.</div>
      </div>
      <div class="vertical-item">
        <div class="vertical-num">02</div>
        <div class="vertical-name">Navigation GPS</div>
        <div class="vertical-desc">Instructions générées contextuellement. Waze, TomTom.</div>
      </div>
      <div class="vertical-item">
        <div class="vertical-num">03</div>
        <div class="vertical-name">Éducation</div>
        <div class="vertical-desc">Exercices générés en amont. Duolingo, Babbel.</div>
      </div>
      <div class="vertical-item">
        <div class="vertical-num">04</div>
        <div class="vertical-name">Cinéma & séries</div>
        <div class="vertical-desc">Sous-titres et didascalies. Netflix, Amazon Prime.</div>
      </div>
      <div class="vertical-item">
        <div class="vertical-num">05</div>
        <div class="vertical-name">Jeu vidéo</div>
        <div class="vertical-desc">Dialogues PNJ et interfaces. PlayStation, Xbox, Steam.</div>
      </div>
      <div class="vertical-item">
        <div class="vertical-num">06</div>
        <div class="vertical-name">Webtoon</div>
        <div class="vertical-desc">Bulles de dialogue. Naver Webtoon, Tapas.</div>
      </div>
      <div class="vertical-item">
        <div class="vertical-num">07</div>
        <div class="vertical-name">Littérature numérique</div>
        <div class="vertical-desc">Narration et descriptions. Wattpad, Royal Road.</div>
      </div>
      <div class="vertical-item">
        <div class="vertical-num">08</div>
        <div class="vertical-name">Romans audio</div>
        <div class="vertical-desc">Texte avant synthèse vocale. Audible, Storytel.</div>
      </div>
      <div class="vertical-item">
        <div class="vertical-num">09</div>
        <div class="vertical-name">LLMs conversationnels</div>
        <div class="vertical-desc">Recommandations contextuelles. ChatGPT, Perplexity.</div>
      </div>
    </div>
  </div>

</div>


<!-- ════════════════════════════ PAGE TARIFS ═════════════════════ -->
<div class="page" id="page-tarifs">

  <div class="tarifs-hero">
    <div class="section-label">Modèle économique</div>
    <h1 class="hero-title" style="font-family:'Syne',sans-serif;font-size:clamp(40px,6vw,80px);font-weight:800;letter-spacing:-3px;color:#fff;line-height:1;">
      Licensing fixe.<br><em style="color:var(--neural)">Performance</em><br>partagée.
    </h1>
  </div>

  <div class="pricing-grid">
    <div class="pricing-card">
      <div class="pricing-tier">Entrée</div>
      <div class="pricing-name">Starter</div>
      <div class="pricing-price">3 000<span>€ / mois</span></div>
      <div class="pricing-note">+ 10% des revenus générés</div>
      <div class="pricing-divider"></div>
      <ul class="pricing-features">
        <li>1 vertical au choix</li>
        <li>Vault jusqu'à 10 marques</li>
        <li>API REST dédiée</li>
        <li>Support technique prioritaire</li>
        <li>Rapport mensuel de performance</li>
      </ul>
      <a href="#" class="pricing-cta" onclick="showPage('contact');return false;">Nous contacter</a>
    </div>

    <div class="pricing-card featured">
      <div class="pricing-tier">Standard</div>
      <div class="pricing-name">Growth</div>
      <div class="pricing-price">8 000<span>€ / mois</span></div>
      <div class="pricing-note">+ 15% des revenus générés</div>
      <div class="pricing-divider"></div>
      <ul class="pricing-features">
        <li>3 verticales au choix</li>
        <li>Vault jusqu'à 30 marques</li>
        <li>Onboarding vault dédié</li>
        <li>API REST + webhooks</li>
        <li>Dashboard analytique temps réel</li>
        <li>Contrat 12 mois — renouvellement auto</li>
      </ul>
      <a href="#" class="pricing-cta" onclick="showPage('contact');return false;">Nous contacter</a>
    </div>

    <div class="pricing-card">
      <div class="pricing-tier">Enterprise</div>
      <div class="pricing-name">Platform</div>
      <div class="pricing-price">Sur<span> mesure</span></div>
      <div class="pricing-note">Contrat 1 à 3 ans — exclusivité sectorielle</div>
      <div class="pricing-divider"></div>
      <ul class="pricing-features">
        <li>Toutes les verticales</li>
        <li>Vault illimité — catalogue dynamique</li>
        <li>Intégration pipeline sur mesure</li>
        <li>Exclusivité sectorielle négociable</li>
        <li>SLA garanti 99.9%</li>
        <li>Account Manager dédié</li>
        <li>Accès au roadmap produit</li>
      </ul>
      <a href="#" class="pricing-cta" onclick="showPage('contact');return false;">Nous contacter</a>
    </div>
  </div>

  <div class="revenue-section">
    <div class="section-label">Comment ça fonctionne</div>
    <h2 class="section-title">Vous gagnez plus.<br>Nous gagnons plus.</h2>
    <div class="revenue-grid">
      <div class="revenue-item">
        <div class="revenue-label">Licensing fixe</div>
        <div class="revenue-title">Prévisibilité totale</div>
        <div class="revenue-desc">Un montant mensuel fixe couvre l'accès au moteur Synapso, l'API, le vault calibré et le support. Vos équipes planifient sans surprise.</div>
      </div>
      <div class="revenue-item">
        <div class="revenue-label">Commission performance</div>
        <div class="revenue-title">Alignement des intérêts</div>
        <div class="revenue-desc">Un pourcentage des revenus publicitaires générés par Synapso. Plus votre plateforme performe, plus nous investissons dans votre réussite.</div>
      </div>
      <div class="revenue-item">
        <div class="revenue-label">Onboarding vault</div>
        <div class="revenue-title">Déploiement en 30 jours</div>
        <div class="revenue-desc">Nos équipes structurent votre catalogue de marques dans le format Synapso. Un investissement unique qui crée immédiatement du switching cost.</div>
      </div>
      <div class="revenue-item">
        <div class="revenue-label">Données de performance</div>
        <div class="revenue-title">Intelligence accumulée</div>
        <div class="revenue-desc">Chaque mois d'utilisation affine les paramètres. La précision du moteur croît avec le temps — votre avantage concurrentiel aussi.</div>
      </div>
    </div>
  </div>

</div>


<!-- ════════════════════════════ PAGE CONTACT ════════════════════ -->
<div class="page" id="page-contact">
  <div class="contact-wrap">
    <div class="contact-info">
      <div class="section-label">Nous contacter</div>
      <h1 class="contact-title">
        Parlons de votre <em>inventaire</em> non monétisé.
      </h1>
      <p class="contact-desc">
        Que vous soyez une plateforme de streaming, un éditeur de jeux, une régie publicitaire ou un fonds d'investissement — Synapso a une proposition concrète pour vous.
      </p>
      <div class="contact-methods">
        <a href="mailto:contact@coreaccess.io" class="contact-method">
          <div class="contact-method-icon">EMAIL</div>
          <div>
            <div class="contact-method-label">Général</div>
            <div class="contact-method-value">contact@coreaccess.io</div>
          </div>
        </a>
        <a href="mailto:partnerships@coreaccess.io" class="contact-method">
          <div class="contact-method-icon">BIZDEV</div>
          <div>
            <div class="contact-method-label">Partenariats & Licensing</div>
            <div class="contact-method-value">partnerships@coreaccess.io</div>
          </div>
        </a>
        <a href="mailto:legal@coreaccess.io" class="contact-method">
          <div class="contact-method-icon">LEGAL</div>
          <div>
            <div class="contact-method-label">Juridique & IP</div>
            <div class="contact-method-value">legal@coreaccess.io</div>
          </div>
        </a>
      </div>
    </div>

    <form class="contact-form" onsubmit="return false;">
      <div class="form-group">
        <label class="form-label">Société</label>
        <input type="text" class="form-input" placeholder="Votre entreprise"/>
      </div>
      <div class="form-group">
        <label class="form-label">Nom & Prénom</label>
        <input type="text" class="form-input" placeholder="Prénom Nom"/>
      </div>
      <div class="form-group">
        <label class="form-label">Email professionnel</label>
        <input type="email" class="form-input" placeholder="vous@societe.com"/>
      </div>
      <div class="form-group">
        <label class="form-label">Objet de la demande</label>
        <select class="form-select form-input">
          <option value="">Sélectionner...</option>
          <option>Licensing Synapso</option>
          <option>Partenariat commercial</option>
          <option>Investissement / M&A</option>
          <option>Démo technique</option>
          <option>Presse & médias</option>
          <option>Autre</option>
        </select>
      </div>
      <div class="form-group">
        <label class="form-label">Message</label>
        <textarea class="form-textarea" placeholder="Décrivez votre projet ou votre besoin..."></textarea>
      </div>
      <button type="submit" class="form-submit">
        Envoyer →
      </button>
    </form>
  </div>
</div>


<!-- ════════════════════════════ PAGE ABOUT ══════════════════════ -->
<div class="page" id="page-about">
  <div class="about-hero">
    <div class="section-label">CoreAccess</div>
    <p class="about-manifesto">
      Nous ne stockons pas de données. Nous ne traquons personne. Nous <em>transformons</em> le langage pour y inscrire de la valeur commerciale — de façon invisible, précise, et brevetée.
    </p>

    <div class="about-grid">
      <div class="about-block">
        <div class="about-block-label">Vision</div>
        <div class="about-block-title">L'intelligence sémantique au service de la publicité</div>
        <div class="about-block-text">CoreAccess développe des technologies de placement publicitaire vectoriel dans le contenu naturel. Synapso est notre premier produit — un moteur asset-light qui transforme n'importe quel texte en espace publicitaire cohérent, sans données personnelles, sans rupture de l'expérience utilisateur.</div>
      </div>
      <div class="about-block">
        <div class="about-block-label">Positionnement</div>
        <div class="about-block-title">Privacy-first par construction</div>
        <div class="about-block-text">Dans un monde post-cookies, post-RGPD, post-DSA, la publicité contextuelle sémantique est la seule alternative légalement viable à grande échelle. Synapso n'utilise aucune donnée personnelle. Il analyse le contenu — pas l'utilisateur. Nativement conforme. Structurellement supérieur.</div>
      </div>
      <div class="about-block">
        <div class="about-block-label">Propriété intellectuelle</div>
        <div class="about-block-title">Brevet en cours de dépôt</div>
        <div class="about-block-text">Le pipeline Synapso — détection POS, scoring vectoriel contextuel, accord grammatical, contrainte prosodique — fait l'objet d'une demande de brevet INPI et d'un dépôt provisoire USPTO. La méthode, les verticales et le système de vault calibré constituent des actifs IP défendables.</div>
      </div>
      <div class="about-block">
        <div class="about-block-label">Marché</div>
        <div class="about-block-title">$217 milliards. 13.3% de croissance annuelle.</div>
        <div class="about-block-text">Le marché mondial de la publicité contextuelle atteindra $592 milliards en 2030. Synapso adresse un sous-segment de $28 milliards encore inexploité — les contenus textuels générés algorithmiquement dans 9 verticales médias.</div>
      </div>
    </div>
  </div>

  <div class="tech-section">
    <div class="section-label">Stack technique</div>
    <h2 class="section-title">Asset-light.<br>API-native.</h2>

    <div class="tech-row">
      <div class="tech-num">01</div>
      <div class="tech-name">Claude Sonnet</div>
      <div class="tech-desc">Modèle de langage via Anthropic API sur Google Cloud Vertex AI. Zéro modèle local. Zéro infrastructure GPU. Coût marginal quasi nul à l'échelle.</div>
    </div>
    <div class="tech-row">
      <div class="tech-num">02</div>
      <div class="tech-name">Pipeline vectoriel</div>
      <div class="tech-desc">Détection POS → scoring sémantique contextuel (fenêtre 5 mots) → accord grammatical → contrainte prosodique. Retour JSON structuré.</div>
    </div>
    <div class="tech-row">
      <div class="tech-num">03</div>
      <div class="tech-name">Brand Vault</div>
      <div class="tech-desc">Catalogue sémantique par client. Seuils individuels par marque. Système de verticales. Données de performance propriétaires accumulées dans le temps.</div>
    </div>
    <div class="tech-row">
      <div class="tech-num">04</div>
      <div class="tech-name">API REST</div>
      <div class="tech-desc">Endpoint HTTP consommable par n'importe quelle plateforme. Intégration dans les pipelines de génération de contenu existants en moins de 30 jours.</div>
    </div>
    <div class="tech-row">
      <div class="tech-num">05</div>
      <div class="tech-name">Google Cloud</div>
      <div class="tech-desc">Infrastructure Vertex AI. Scalabilité infinie sans coût fixe. Déploiement mondial. Conformité RGPD native via les datacenters européens.</div>
    </div>
  </div>
</div>


<!-- FOOTER -->
<footer>
  <div class="footer-logo">Core<span>Access</span> · Synapso</div>
  <div class="footer-note">© 2026 CoreAccess — Tous droits réservés</div>
  <div class="footer-patent">Brevet en cours de dépôt · INPI + USPTO</div>
</footer>


<script>
// ── CURSEUR ──────────────────────────────────────────────────────
const cursor = document.getElementById('cursor');
const ring   = document.getElementById('cursor-ring');
let mx=0,my=0,rx=0,ry=0;

document.addEventListener('mousemove',e=>{
  mx=e.clientX; my=e.clientY;
  cursor.style.left=mx+'px'; cursor.style.top=my+'px';
});

function animRing(){
  rx+=(mx-rx)*0.12; ry+=(my-ry)*0.12;
  ring.style.left=rx+'px'; ring.style.top=ry+'px';
  requestAnimationFrame(animRing);
}
animRing();

document.querySelectorAll('a,button,input,textarea,select,.demo-card,.vertical-item,.pricing-card,.revenue-item,.about-block').forEach(el=>{
  el.addEventListener('mouseenter',()=>{
    cursor.style.transform='translate(-50%,-50%) scale(2)';
    ring.style.transform='translate(-50%,-50%) scale(1.5)';
    ring.style.borderColor='rgba(212,255,0,0.8)';
  });
  el.addEventListener('mouseleave',()=>{
    cursor.style.transform='translate(-50%,-50%) scale(1)';
    ring.style.transform='translate(-50%,-50%) scale(1)';
    ring.style.borderColor='rgba(212,255,0,0.4)';
  });
});

// ── NAVIGATION ───────────────────────────────────────────────────
function showPage(id){
  document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
  document.querySelectorAll('[data-page]').forEach(a=>a.classList.remove('active'));
  document.getElementById('page-'+id).classList.add('active');
  document.querySelectorAll('[data-page="'+id+'"]').forEach(a=>a.classList.add('active'));
  window.scrollTo(0,0);
}

// ── NEURAL CANVAS ─────────────────────────────────────────────────
const canvas = document.getElementById('neural-canvas');
const ctx    = canvas.getContext('2d');

let nodes=[], W, H;
const NODE_COUNT = 80;

function resize(){
  W=canvas.width=window.innerWidth;
  H=canvas.height=window.innerHeight;
}

function initNodes(){
  nodes=[];
  for(let i=0;i<NODE_COUNT;i++){
    nodes.push({
      x:Math.random()*W, y:Math.random()*H,
      vx:(Math.random()-0.5)*0.3,
      vy:(Math.random()-0.5)*0.3,
      r:Math.random()*2+1,
      pulse:Math.random()*Math.PI*2
    });
  }
}

function drawNeural(){
  ctx.clearRect(0,0,W,H);
  const t=Date.now()*0.001;

  // Connexions
  for(let i=0;i<nodes.length;i++){
    for(let j=i+1;j<nodes.length;j++){
      const dx=nodes[i].x-nodes[j].x;
      const dy=nodes[i].y-nodes[j].y;
      const d=Math.sqrt(dx*dx+dy*dy);
      if(d<160){
        const alpha=(1-d/160)*0.25;
        ctx.beginPath();
        ctx.strokeStyle=`rgba(212,255,0,${alpha})`;
        ctx.lineWidth=0.5;
        ctx.moveTo(nodes[i].x,nodes[i].y);
        ctx.lineTo(nodes[j].x,nodes[j].y);
        ctx.stroke();
      }
    }
  }

  // Noeuds
  nodes.forEach((n,i)=>{
    n.pulse+=0.02;
    const glow=0.5+0.5*Math.sin(n.pulse);

    ctx.beginPath();
    ctx.arc(n.x,n.y,n.r,0,Math.PI*2);
    ctx.fillStyle=`rgba(212,255,0,${0.4+glow*0.4})`;
    ctx.fill();

    // Mouvement
    n.x+=n.vx; n.y+=n.vy;
    if(n.x<0||n.x>W) n.vx*=-1;
    if(n.y<0||n.y>H) n.vy*=-1;
  });

  requestAnimationFrame(drawNeural);
}

resize();
initNodes();
drawNeural();
window.addEventListener('resize',()=>{resize();initNodes();});

// Interaction souris avec le réseau neural
document.addEventListener('mousemove',e=>{
  nodes.forEach(n=>{
    const dx=n.x-e.clientX, dy=n.y-e.clientY;
    const d=Math.sqrt(dx*dx+dy*dy);
    if(d<120){
      n.vx+=dx/d*0.08;
      n.vy+=dy/d*0.08;
      const max=1.2;
      if(Math.abs(n.vx)>max) n.vx=Math.sign(n.vx)*max;
      if(Math.abs(n.vy)>max) n.vy=Math.sign(n.vy)*max;
    }
  });
});
</script>
</body>
</html>
