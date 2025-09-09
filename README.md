<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>MindBreath — Guided Breathwork for Calm & Focus</title>
  <meta name="description" content="MindBreath helps you practice calm, guided breathing and track your progress with a simple, beautiful interface." />

  <!-- Open Graph / Twitter -->
  <meta property="og:title" content="MindBreath — Guided Breathwork for Calm & Focus" />
  <meta property="og:description" content="Practice calm, guided breathing. Reduce stress. Track progress.">
  <meta property="og:type" content="website" />
  <meta property="og:url" content="https://carlossemeao.github.io/MindBreath-Lab/" />
  <!-- Optional: replace with your social preview -->
  <meta property="og:image" content="assets/og-cover.png" />

  <style>
    :root{
      --bg:#0C1413;
      --card:#0f1917;
      --ink:#E5E7EB;
      --muted:#A7B0B3;
      --teal:#14B8A6;
      --ring: rgba(20,184,166,.25);
    }
    *{box-sizing:border-box}
    html,body{margin:0;padding:0;background:var(--bg);color:var(--ink);font-family:ui-sans-serif,system-ui,-apple-system,Segoe UI,Roboto,Inter,Helvetica,Arial;}
    a{color:var(--teal);text-decoration:none}
    a:hover{text-decoration:underline}
    .wrap{max-width:980px;margin:0 auto;padding:24px}
    header{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:8px 0 24px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:40px;height:40px;border-radius:12px;background:linear-gradient(135deg,#20B2AA,#008080);}
    nav a{margin-left:18px;color:var(--muted)}
    nav a:hover{color:var(--ink)}
    .hero{display:grid;grid-template-columns:1.15fr .85fr;gap:28px;align-items:center;padding:28px;border:1px solid rgba(255,255,255,.06);background:linear-gradient(180deg,rgba(32,178,170,.06),rgba(32,178,170,0));border-radius:20px}
    .kicker{color:var(--teal);font-weight:600;letter-spacing:.04em}
    h1{margin:.25rem 0 0;font-size:40px;line-height:1.1}
    .sub{color:var(--muted);margin-top:10px;font-size:18px}
    .cta{display:flex;gap:14px;flex-wrap:wrap;margin-top:18px}
    .badge{display:inline-flex;align-items:center;gap:10px;padding:12px 16px;border-radius:12px;background:var(--card);border:1px solid rgba(255,255,255,.08)}
    .badge span{display:block;line-height:1}
    .badge small{color:var(--muted);display:block}
    .ghost{opacity:.6}
    .shot{border-radius:18px;border:1px solid rgba(255,255,255,.08);background:#09110f;min-height:300px;display:flex;align-items:center;justify-content:center;color:#6f7b7d}
    .features{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:34px}
    .card{background:var(--card);border:1px solid rgba(255,255,255,.06);border-radius:16px;padding:18px}
    .card h3{margin:0 0 6px}
    .grid-2{display:grid;grid-template-columns:1fr 1fr;gap:16px;margin-top:16px}
    footer{margin:44px 0 12px;color:var(--muted);display:flex;flex-wrap:wrap;gap:10px;justify-content:space-between;align-items:center}
    .links{display:flex;gap:16px;align-items:center}
    .pill{padding:8px 12px;border-radius:999px;border:1px solid rgba(255,255,255,.08);background:var(--card);color:var(--muted)}
    .ring{box-shadow:0 0 0 8px var(--ring)}
    @media (max-width: 900px){
      .hero{grid-template-columns:1fr}
      .features{grid-template-columns:1fr}
      .grid-2{grid-template-columns:1fr}
    }
  </style>
</head>
<body>
  <div class="wrap">
    <header>
      <div class="brand">
        <!-- Replace with your real icon, e.g. assets/icon/MB-Icon.png -->
        <div class="logo" aria-hidden="true"></div>
        <strong>MindBreath</strong>
      </div>
      <nav>
        <a href="./support.html">Support</a>
        <a href="./privacy.html">Privacy</a>
        <!-- You can add a Blog/Changelog later -->
      </nav>
    </header>

    <section class="hero">
      <div>
        <div class="kicker">Guided Breathwork</div>
        <h1>Breathe better. Feel calmer.<br/>Track your progress.</h1>
        <p class="sub">
          MindBreath gives you simple, beautiful breathing sessions (inhale · hold · exhale · rest),
          gentle haptics, and a clear progress view. Designed for focus and calm — anytime.
        </p>
        <div class="cta">
          <!-- Replace href with your real store links -->
          <a class="badge ring" href="#" aria-label="Download on the App Store">
            <span>
              <small>Download on the</small>
              <strong>App Store</strong>
            </span>
          </a>
          <a class="badge ghost" href="#" aria-label="Get it on Google Play" title="Coming soon">
            <span>
              <small>Get it on</small>
              <strong>Google Play</strong>
            </span>
          </a>
        </div>
      </div>
      <div class="shot">App screenshot placeholder (add /assets/shot.png)</div>
    </section>

    <section class="features">
      <div class="card">
        <h3>Beautiful & minimal</h3>
        <p>Clean Cupertino design with soft teal accents and a calming “rings globe” animation.</p>
      </div>
      <div class="card">
        <h3>Haptics you can feel</h3>
        <p>Subtle taps mark phase changes so you can keep eyes off the screen.</p>
      </div>
      <div class="card">
        <h3>Progress that motivates</h3>
        <p>See your weekly bars, streaks, and monthly totals. Export CSV in a tap.</p>
      </div>
    </section>

    <section class="grid-2">
      <div class="card">
        <h3>Custom timing</h3>
        <p>Choose beginner, balanced, or advanced — or set your own inhale/hold/exhale/rest times.</p>
      </div>
      <div class="card">
        <h3>Light, Dark, or System</h3>
        <p>Match your device appearance or pick your favorite look.</p>
      </div>
    </section>

    <footer>
      <div class="links">
        <a class="pill" href="./support.html">Support</a>
        <a class="pill" href="./privacy.html">Privacy</a>
      </div>
      <div>© <span id="y"></span> MindBreath</div>
    </footer>
  </div>

  <script>
    document.getElementById('y').textContent = new Date().getFullYear();
  </script>
</body>
</html>
