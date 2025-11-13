<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Bold Mark — Make Your Mark. Boldly.</title>
  <meta name="description" content="Bold Mark — private luxury brand design & strategy studio. Crafting bold and iconic brand identity and strategy that elevates perception, builds trust, and inspires action."/>
  <style>
    :root{
      --bg: #F8F6F3;
      --text: #0B0B0B;
      --muted: #7A746F;
      --gold: #C9B89A;
      --max: 1100px;
      --radius: 10px;
      --font: 'Satoshi', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    html,body{height:100%;}
    body{
      margin:0;
      font-family: var(--font);
      background:var(--bg);
      color:var(--text);
      line-height:1.6;
      -webkit-font-smoothing:antialiased;
    }
    .container{max-width:var(--max);margin:0 auto;padding:48px 24px;}
    header{display:flex;align-items:center;justify-content:space-between;padding:18px 0;}
    .logo{display:flex;align-items:center;gap:12px;}
    .logo svg{width:56px;height:56px;}
    .brand{font-weight:700;letter-spacing:1px;}
    nav{display:flex;gap:20px;align-items:center;}
    nav a{color:var(--muted);text-decoration:none;font-size:14px;}
    .hero{display:grid;grid-template-columns:1fr 420px;gap:48px;align-items:center;padding:48px 0;}
    .hero h1{font-size:44px;margin:0 0 18px;font-weight:700;}
    .hero p.lead{font-size:18px;color:var(--muted);max-width:60%;}
    .cta-buttons{margin-top:24px;display:flex;gap:12px;}
    .btn{padding:12px 18px;border-radius:6px;border:1px solid transparent;font-weight:600;cursor:pointer;}
    .btn-primary{background:#0B0B0B;color:#fff;}
    .btn-ghost{background:transparent;border:1px solid rgba(11,11,11,0.08);color:var(--text);}
    .card{background:#fff;padding:28px;border-radius:12px;box-shadow:0 8px 30px rgba(11,11,11,0.06);}
    section{padding:36px 0;border-top:1px solid rgba(11,11,11,0.03);}
    .section-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:18px;}
    .service{background:#fff;padding:20px;border-radius:8px;min-height:120px;display:flex;flex-direction:column;gap:8px;}
    .service h5{margin:0;}
    .service p{margin:0;color:var(--muted);font-size:14px;}
    .mission, .vision{background:#fff;padding:22px;border-radius:10px;}
    .mission h3, .vision h3{margin:0 0 8px;}
    footer{padding:36px 0;text-align:center;color:var(--muted);}
    .whatsapp{position:fixed;right:20px;bottom:20px;background:#25D366;color:#fff;width:58px;height:58px;border-radius:50%;display:flex;align-items:center;justify-content:center;box-shadow:0 8px 24px rgba(0,0,0,0.14);border:4px solid rgba(255,255,255,0.15);text-decoration:none;}
    .whatsapp svg{width:28px;height:28px;}
    @media (max-width:900px){
      .hero{grid-template-columns:1fr;}
      .hero p.lead{max-width:100%;}
    }
  </style>
</head>
<body>
  <header class="container">
    <div class="logo">
      <!-- Simple BM Logo -->
      <svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
        <rect width="100" height="100" rx="12" fill="black"/>
        <text x="50%" y="58%" text-anchor="middle" font-family="Arial" font-size="46" font-weight="700" fill="white">BM</text>
      </svg>
      <div>
        <div class="brand">BOLD MARK</div>
        <div style="font-size:12px;color:var(--muted);">Brand Strategy & Design</div>
      </div>
    </div>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main class="container">
    <section class="hero">
      <div>
        <h1>Make Your Mark. <span style="color:var(--gold)">Boldly.</span></h1>
        <p class="lead">We craft timeless brands that whisper luxury and speak results. Bold Mark blends strategy, narrative, and meticulous design to elevate perception and create enduring value.</p>
        <div class="cta-buttons">
          <button class="btn btn-primary" onclick="openWhatsApp()">Request Private Consultation</button>
        </div>
      </div>

      <aside class="card">
        <h4>Welcome to Bold Mark</h4>
        <p style="color:var(--muted);margin-top:12px;">A private luxury brand design and strategy studio for visionary founders ready to make their mark.</p>
      </aside>
    </section>

    <section id="about">
      <h2>About Bold Mark</h2>
      <p style="color:var(--muted);max-width:70%;">Bold Mark is a private luxury brand design and strategy studio. We help visionary founders and businesses build timeless brands through clarity, storytelling, and design. We accept a limited number of clients each quarter to ensure focus and depth.</p>

      <div style="display:grid;grid-template-columns:1fr 1fr;gap:20px;margin-top:24px;">
        <div class="mission">
          <h3>Mission</h3>
          <p>Crafting bold and iconic brand identity and strategy that elevates perception, builds trust and inspires action.</p>
        </div>
        <div class="vision">
          <h3>Vision</h3>
          <p>To be the creative force and mind behind the world's most memorable and meaningful brands.</p>
        </div>
      </div>
    </section>

    <section id="services">
      <h2>Our Services</h2>
      <div class="section-grid">
        <div class="service">
          <h5>Brand Design</h5>
          <p>Visual identity, logo systems, typography and brand assets crafted for timeless appeal.</p>
        </div>
        <div class="service">
          <h5>Brand Strategy</h5>
          <p>Positioning, messaging, and brand frameworks that define how you move and communicate.</p>
        </div>
        <div class="service">
          <h5>Social Media Management</h5>
          <p>Curated storytelling, content systems and visuals that sustain brand consistency and growth.</p>
        </div>
        <div class="service">
          <h5>Brand Consultation</h5>
          <p>Strategic sessions and audits to help brands refine, reposition, and evolve with clarity.</p>
        </div>
      </div>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p style="color:var(--muted);max-width:70%;">Request a private consultation or start a chat via WhatsApp. We accept limited clients per quarter to maintain focus and exclusivity.</p>
    </section>
  </main>

  <footer>
    <div class="container">
      <div>© <strong>Bold Mark</strong> — Make Your Mark. Boldly.</div>
      <div style="color:var(--muted);font-size:13px;">Designed with precision and purpose.</div>
    </div>
  </footer>

  <!-- WhatsApp floating button -->
  <a class="whatsapp" href="https://wa.me/2348137524677" target="_blank" rel="noopener noreferrer" aria-label="Chat on WhatsApp">
    <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
      <path d="M20.52 3.48A11.95 11.95 0 0 0 12 0C5.373 0 .01 4.743.01 10.586c0 1.862.5 3.69 1.45 5.303L0 24l8.643-2.283c1.474.404 3.01.635 4.357.635 6.627 0 12-4.743 12-10.586 0-2.833-1.09-5.41-3.48-7.286z" fill="#25D366"/>
      <path d="M17.34 15.01c-.44-.22-2.6-1.28-3.01-1.43-.41-.15-.71-.22-1.01.22s-1.16 1.43-1.41 1.72c-.25.29-.5.33-.93.11-.44-.22-1.87-.69-3.57-2.2-1.32-1.24-2.2-2.78-2.45-3.22-.25-.44-.03-.68.19-.9.19-.19.44-.5.66-.75.22-.25.29-.44.44-.73.15-.29.06-.55-.03-.77-.09-.22-1.01-2.44-1.39-3.33-.36-.86-.73-.74-1-.75-.27-.01-.57-.01-.87-.01-.29 0-.76.11-1.16.55-.4.44-1.48 1.44-1.48 3.5 0 2.06 1.52 4.07 1.73 4.36.22.29 2.99 4.6 7.24 6.33 4.24 1.72 4.24 1.15 5 1.08.76-.07 2.43-.99 2.78-1.95.35-.96.35-1.78.24-1.95-.12-.17-.44-.28-.93-.5z" fill="#fff"/>
    </svg>
  </a>

  <script>
    function openWhatsApp(){
      window.open('https://wa.me/2348137524677','_blank');
    }
  </script>
</body>
</html>
