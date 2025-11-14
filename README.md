<!--
/********************************************************************************
 *  STC CREATIVE CLUB - ATTRACTIVE GITHUB PAGE (Single File HTML)
 *
 *  Project : STC Attractive GitHub Page
 *  Author  : PRAVIN SINH RANA
 *  GitHub  : pravinsindaldev-p4
 *  Contact : +91 9313057803
 *  Instagram : @S.T.C_CREATIVE_CLUB
 *
 *  Brief   : Single-file responsive HTML page you can host on GitHub Pages
 *            (repo: pravinsindaldev-p4) or include as project demo page.
 *
 *  Instructions:
 *    1. Save this file as `index.html` in your GitHub Pages repo
 *       (pravinsindaldev-p4.github.io) or add into a project folder.
 *    2. Replace placeholder images in the `assets/` folder or update links.
 *    3. Edit projects and links in the Projects section.
 *
 *  Serial Monitor Branding (separate): there's an on-page "Serial Monitor"
 *  panel below and matching console prints for runtime branding.
 *
 ********************************************************************************/
-->

<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>PRAVIN SINH RANA — STC Creative Club</title>
  <meta name="description" content="STC Creative Club — Robotics, IoT, Workshops. Founder: Pravin Sinh Rana" />

  <!-- Simple, clean CSS. Keep it editable and lightweight. -->
  <style>
    :root{
      --bg:#0f1724; --card:#0b1220; --muted:#9aa7b2; --accent:#00d4a6; --glass: rgba(255,255,255,0.04);
      --radius:14px; --pad:18px; --maxw:1000px;
      font-family: Inter, ui-sans-serif, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
    }
    *{box-sizing:border-box}
    body{margin:0;min-height:100vh;background:linear-gradient(180deg,#071026 0%, #071028 60%);color:#e6eef3;display:flex;align-items:center;justify-content:center;padding:36px}
    .wrap{width:100%;max-width:var(--maxw);}
    .hero{display:grid;grid-template-columns:160px 1fr;gap:18px;align-items:center;background:linear-gradient(90deg, rgba(255,255,255,0.02), transparent);padding:var(--pad);border-radius:var(--radius);box-shadow:0 8px 30px rgba(2,6,23,0.6)}
    .avatar{width:140px;height:140px;border-radius:16px;overflow:hidden;border:3px solid rgba(255,255,255,0.06);display:flex;align-items:center;justify-content:center;background:linear-gradient(135deg,#071026,#0b1530)}
    .avatar img{width:100%;height:100%;object-fit:cover}
    h1{font-size:22px;margin:0 0 6px 0}
    p.lead{margin:0;color:var(--muted)}

    .badges{margin-top:12px;display:flex;gap:8px;flex-wrap:wrap}
    .badge{background:var(--glass);padding:8px 10px;border-radius:999px;font-size:13px;color:var(--muted)}

    .grid{display:grid;grid-template-columns:1fr 360px;gap:18px;margin-top:18px}
    .card{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:18px;border-radius:12px}

    .skills{display:flex;gap:8px;flex-wrap:wrap}
    .skill{padding:6px 8px;border-radius:8px;background:rgba(255,255,255,0.02);font-size:13px}

    .projects{display:grid;gap:12px}
    .proj{display:flex;gap:12px;align-items:center;padding:10px;border-radius:10px;background:linear-gradient(90deg, rgba(255,255,255,0.01), transparent)}
    .proj img{width:80px;height:60px;border-radius:8px;object-fit:cover}
    .proj .meta{flex:1}
    .proj h4{margin:0 0 4px 0;font-size:15px}
    .proj p{margin:0;color:var(--muted);font-size:13px}

    .serial{background:#02111a;padding:12px;border-radius:10px;font-family:monospace;color:#9be6cf;height:160px;overflow:auto}
    .serial .line{opacity:0.95}

    footer{margin-top:18px;text-align:center;color:var(--muted);font-size:13px}

    /* Responsive */
    @media (max-width:900px){.grid{grid-template-columns:1fr} .hero{grid-template-columns:110px 1fr} .avatar{width:110px;height:110px}}
  </style>
</head>
<body>
  <div class="wrap">

    <!-- HERO -->
    <section class="hero">
      <div class="avatar">
        <!-- Replace image link with your photo in assets/profile.jpg -->
        <img src="https://avatars.githubusercontent.com/u/0?v=4" alt="Pravin Profile" id="pfp">
      </div>

      <div>
        <h1>PRAVIN SINH RANA <span style="color:var(--accent);font-weight:600">— STC Creative Club</span></h1>
        <p class="lead">Founder • STEM Coach • Robotics, IoT & Workshop Mentor<br/>Navsari, Gujarat • +91 9313057803 • <a href="https://www.instagram.com/S.T.C_CREATIVE_CLUB" style="color:var(--accent);text-decoration:none">@S.T.C_CREATIVE_CLUB</a></p>

        <div class="badges">
          <div class="badge">STC Creative Club</div>
          <div class="badge">Founder</div>
          <div class="badge">Robotics & IoT</div>
          <div class="badge">pravinsindaldev-p4</div>
        </div>
      </div>
    </section>

    <!-- MAIN GRID -->
    <div class="grid">
      <div>
        <div class="card">
          <h3 style="margin:0 0 8px 0">About Me</h3>
          <p style="color:var(--muted);margin:0 0 10px 0">I run STEM workshops across Dang and Navsari, build low-cost automation for local problems, and coach students in national robotics competitions. This page is a demo GitHub Pages profile for <strong>pravinsindaldev-p4</strong>.</p>

          <h4 style="margin-top:12px">Skills</h4>
          <div class="skills">
            <div class="skill">Arduino / ESP32</div>
            <div class="skill">C / C++</div>
            <div class="skill">Python</div>
            <div class="skill">HTML / CSS / JS</div>
            <div class="skill">Embedded Web UI</div>
          </div>

          <h4 style="margin-top:12px">Featured Projects</h4>
          <div class="projects">
            <a class="proj" href="https://github.com/pravinsindaldev-p4/hygienic-food-container" target="_blank">
              <img src="https://raw.githubusercontent.com/pravinsindaldev-p4/pravinsindaldev-p4/main/assets/hygienic-thumb.png" alt="Hygienic">
              <div class="meta"><h4>Hygienic Food Container</h4><p>ESP8266 + DHT11 + MQ4 + UV — Spoilage detection & disinfect mode</p></div>
            </a>

            <a class="proj" href="https://github.com/pravinsindaldev-p4/smart-flower-pot" target="_blank">
              <img src="https://raw.githubusercontent.com/pravinsindaldev-p4/pravinsindaldev-p4/main/assets/flowerpot-thumb.png" alt="Flowerpot">
              <div class="meta"><h4>Smart Flower Pot</h4><p>NodeMCU AP + soil moisture + local web dashboard</p></div>
            </a>

            <a class="proj" href="https://github.com/pravinsindaldev-p4/esp-fish-feeder" target="_blank">
              <img src="https://raw.githubusercontent.com/pravinsindaldev-p4/pravinsindaldev-p4/main/assets/fishfeeder-thumb.png" alt="Fish Feeder">
              <div class="meta"><h4>ESP Fish Feeder</h4><p>Time-based feeding with web scheduler and multi-device sync</p></div>
            </a>
          </div>

        </div>

        <!-- Contact / CTA card -->
        <div style="height:12px"></div>
        <div class="card" style="margin-top:12px;display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap">
          <div>
            <h4 style="margin:0">Get in touch</h4>
            <p style="margin:4px 0 0 0;color:var(--muted)">Want me to demo a workshop, collaborate or speak? Reach out.</p>
            <p style="margin:8px 0 0 0;font-family:monospace;color:var(--muted)">Phone: +91 9313057803</p>
          </div>
          <div style="text-align:center">
            <a href="https://github.com/pravinsindaldev-p4" target="_blank" style="display:inline-block;padding:10px 14px;border-radius:10px;background:linear-gradient(90deg,var(--accent),#6ee7c4);color:#042026;font-weight:700;text-decoration:none">View GitHub</a>
          </div>
        </div>

      </div>

      <!-- RIGHT COLUMN -->
      <aside>
        <div class="card">
          <h4 style="margin:0 0 8px 0">Quick Stats</h4>
          <p style="color:var(--muted);margin:0 0 12px 0">(Live stats widgets shown below — replace username)</p>
          <div style="display:flex;flex-direction:column;gap:8px">
            <img src="https://github-readme-stats.vercel.app/api?username=pravinsindaldev-p4&show_icons=true&count_private=true" alt="stats" style="width:100%;border-radius:8px" />
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pravinsindaldev-p4&layout=compact" alt="langs" style="width:100%;border-radius:8px" />
          </div>
        </div>

        <div style="height:12px"></div>

        <div class="card">
          <h4 style="margin:0 0 8px 0">Serial Monitor — STC CREATIVE CLUB</h4>
          <div id="serial" class="serial" aria-live="polite"></div>
          <small style="color:var(--muted)">This area mimics a serial monitor for branding and quick runtime logs.</small>
        </div>

      </aside>
    </div>

    <footer>
      <div>Made with ❤ by PRAVIN SINH RANA — STC Creative Club • GitHub: <strong>pravinsindaldev-p4</strong></div>
    </footer>

  </div>

  <!--
    Inline JS: Handles serial monitor prints and small interactive niceties.
    Each function is documented with comments for clarity as requested.
  -->
  <script>
    /**********************************************************************
     * STC Serial Monitor - Console & On-page Branding
     * Purpose: Provide a serial-like startup print for project identity.
     * Author : PRAVIN SINH RANA
     * Contact: +91 9313057803
     * Instagram: @S.T.C_CREATIVE_CLUB
     **********************************************************************/

    // Utility: prints a line both to dev console and the on-page serial element
    function stcPrint(line){
      // Console branding (useful when previewing locally)
      console.log('[STC Serial Monitor] ' + line);
      // On-page serial panel (visible to visitors)
      const el = document.getElementById('serial');
      const div = document.createElement('div');
      div.className = 'line';
      div.textContent = '[STC Serial Monitor] ' + line;
      el.appendChild(div);
      el.scrollTop = el.scrollHeight;
    }

    // Startup sequence: prints project header and status
    function startupSequence(){
      stcPrint('Initializing...');
      setTimeout(()=>stcPrint('Welcome - STC CREATIVE CLUB'),300);
      setTimeout(()=>stcPrint('Project : STC Attractive GitHub Page'),600);
      setTimeout(()=>stcPrint('Author  : PRAVIN SINH RANA'),900);
      setTimeout(()=>stcPrint('Contact : +91 9313057803'),1200);
      setTimeout(()=>stcPrint('Instagram: @S.T.C_CREATIVE_CLUB'),1500);
      setTimeout(()=>stcPrint('Status  : READY'),1800);
    }

    // Function: loadProfileImage
    // Purpose : Attempts to load a GitHub avatar for the username and replace default
    // Params  : username (string) - GitHub username
    function loadProfileImage(username){
      const img = document.getElementById('pfp');
      // GitHub avatars are accessible at https://github.com/USERNAME.png
      img.src = `https://github.com/${username}.png`;
      // Fallback: keep existing if not loaded
      img.onerror = ()=>{ img.src = 'https://raw.githubusercontent.com/pravinsindaldev-p4/pravinsindaldev-p4/main/assets/profile-placeholder.png' }
    }

    // Immediately run startup when page loads
    document.addEventListener('DOMContentLoaded', ()=>{
      startupSequence();
      loadProfileImage('pravinsindaldev-p4');
    });
  </script>
</body>
</html>
