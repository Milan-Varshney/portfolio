<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Milan Varshney — Software Developer</title>
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;700&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet" />
  <style>
    *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }

    :root {
      --bg-primary: #0a0e17;
      --bg-secondary: #111827;
      --bg-card: #151d2e;
      --text-primary: #e4e8f1;
      --text-secondary: #8892a8;
      --accent: #38bdf8;
      --accent-glow: rgba(56, 189, 248, 0.15);
      --accent-dim: #1e6fa0;
      --green: #4ade80;
      --border: #1e293b;
      --mono: 'JetBrains Mono', monospace;
      --sans: 'Inter', system-ui, sans-serif;
    }

    html { scroll-behavior: smooth; }

    body {
      font-family: var(--sans);
      background: var(--bg-primary);
      color: var(--text-primary);
      line-height: 1.6;
      overflow-x: hidden;
    }

    /* ── GRID BACKGROUND ── */
    body::before {
      content: '';
      position: fixed;
      inset: 0;
      background-image:
        linear-gradient(rgba(56, 189, 248, 0.03) 1px, transparent 1px),
        linear-gradient(90deg, rgba(56, 189, 248, 0.03) 1px, transparent 1px);
      background-size: 60px 60px;
      pointer-events: none;
      z-index: 0;
    }

    /* ── CURSOR GLOW ── */
    #cursor-glow {
      position: fixed;
      width: 500px;
      height: 500px;
      border-radius: 50%;
      background: radial-gradient(circle, rgba(56,189,248,0.06) 0%, transparent 70%);
      pointer-events: none;
      z-index: 1;
      transform: translate(-50%, -50%);
      transition: left 0.3s ease-out, top 0.3s ease-out;
    }

    /* ── NAV ── */
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 100;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      background: rgba(10, 14, 23, 0.8);
      backdrop-filter: blur(16px);
      border-bottom: 1px solid var(--border);
    }

    .nav-logo {
      font-family: var(--mono);
      font-weight: 700;
      font-size: 1.1rem;
      color: var(--accent);
    }

    .nav-logo span { color: var(--text-secondary); }

    .nav-links { display: flex; gap: 2rem; list-style: none; }

    .nav-links a {
      text-decoration: none;
      color: var(--text-secondary);
      font-size: 0.875rem;
      font-weight: 500;
      letter-spacing: 0.03em;
      transition: color 0.25s;
      position: relative;
    }

    .nav-links a::after {
      content: '';
      position: absolute;
      bottom: -4px;
      left: 0;
      width: 0;
      height: 2px;
      background: var(--accent);
      transition: width 0.25s;
    }

    .nav-links a:hover { color: var(--accent); }
    .nav-links a:hover::after { width: 100%; }

    /* ── SECTIONS ── */
    section {
      position: relative;
      z-index: 2;
      max-width: 1100px;
      margin: 0 auto;
      padding: 6rem 2rem;
    }

    .section-label {
      font-family: var(--mono);
      font-size: 0.8rem;
      color: var(--accent);
      text-transform: uppercase;
      letter-spacing: 0.15em;
      margin-bottom: 0.75rem;
      display: flex;
      align-items: center;
      gap: 0.75rem;
    }

    .section-label::before {
      content: '';
      width: 24px;
      height: 1px;
      background: var(--accent);
    }

    .section-title {
      font-size: clamp(1.75rem, 4vw, 2.5rem);
      font-weight: 700;
      margin-bottom: 1.5rem;
      line-height: 1.2;
    }

    /* ── HERO ── */
    #hero {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding-top: 5rem;
    }

    .hero-tag {
      font-family: var(--mono);
      color: var(--accent);
      font-size: 0.95rem;
      margin-bottom: 1rem;
    }

    .hero-name {
      font-size: clamp(2.5rem, 7vw, 4.5rem);
      font-weight: 700;
      line-height: 1.1;
      margin-bottom: 0.5rem;
    }

    .hero-subtitle {
      font-size: clamp(1.25rem, 3vw, 2rem);
      color: var(--text-secondary);
      font-weight: 300;
      margin-bottom: 2rem;
    }

    /* Terminal block */
    .terminal {
      background: var(--bg-secondary);
      border: 1px solid var(--border);
      border-radius: 10px;
      max-width: 620px;
      overflow: hidden;
      margin-bottom: 2.5rem;
    }

    .terminal-bar {
      display: flex;
      align-items: center;
      gap: 6px;
      padding: 10px 14px;
      background: rgba(30, 41, 59, 0.6);
      border-bottom: 1px solid var(--border);
    }

    .terminal-dot {
      width: 11px;
      height: 11px;
      border-radius: 50%;
    }

    .terminal-dot:nth-child(1) { background: #ef4444; }
    .terminal-dot:nth-child(2) { background: #eab308; }
    .terminal-dot:nth-child(3) { background: #22c55e; }

    .terminal-title {
      margin-left: 10px;
      font-family: var(--mono);
      font-size: 0.75rem;
      color: var(--text-secondary);
    }

    .terminal-body {
      padding: 1.25rem 1.5rem;
      font-family: var(--mono);
      font-size: 0.85rem;
      line-height: 1.8;
    }

    .terminal-body .prompt { color: var(--green); }
    .terminal-body .cmd { color: var(--text-primary); }
    .terminal-body .output { color: var(--text-secondary); }
    .terminal-body .highlight { color: var(--accent); }

    #typed-output .cursor {
      display: inline-block;
      width: 8px;
      height: 1.1em;
      background: var(--accent);
      vertical-align: text-bottom;
      animation: blink 1s step-end infinite;
    }

    @keyframes blink { 50% { opacity: 0; } }

    /* CTA Buttons */
    .cta-row { display: flex; gap: 1rem; flex-wrap: wrap; }

    .btn {
      display: inline-flex;
      align-items: center;
      gap: 0.5rem;
      padding: 0.75rem 1.75rem;
      border-radius: 8px;
      font-size: 0.9rem;
      font-weight: 600;
      text-decoration: none;
      transition: all 0.25s;
      cursor: pointer;
      border: none;
    }

    .btn-primary {
      background: var(--accent);
      color: var(--bg-primary);
    }

    .btn-primary:hover {
      background: #60ccfc;
      box-shadow: 0 0 24px var(--accent-glow);
      transform: translateY(-2px);
    }

    .btn-outline {
      background: transparent;
      color: var(--accent);
      border: 1px solid var(--accent-dim);
    }

    .btn-outline:hover {
      background: var(--accent-glow);
      border-color: var(--accent);
      transform: translateY(-2px);
    }

    /* ── ABOUT ── */
    .about-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 3rem;
      align-items: start;
    }

    .about-text {
      color: var(--text-secondary);
      font-size: 1rem;
      line-height: 1.8;
    }

    .stats-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 1rem;
    }

    .stat-card {
      background: var(--bg-card);
      border: 1px solid var(--border);
      border-radius: 10px;
      padding: 1.25rem;
      text-align: center;
      transition: border-color 0.25s, transform 0.25s;
    }

    .stat-card:hover {
      border-color: var(--accent-dim);
      transform: translateY(-3px);
    }

    .stat-number {
      font-family: var(--mono);
      font-size: 1.75rem;
      font-weight: 700;
      color: var(--accent);
    }

    .stat-label {
      font-size: 0.8rem;
      color: var(--text-secondary);
      margin-top: 0.25rem;
    }

    /* ── SKILLS ── */
    .skills-container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
      gap: 1.5rem;
    }

    .skill-category {
      background: var(--bg-card);
      border: 1px solid var(--border);
      border-radius: 10px;
      padding: 1.75rem;
      transition: border-color 0.25s, transform 0.25s;
    }

    .skill-category:hover {
      border-color: var(--accent-dim);
      transform: translateY(-3px);
    }

    .skill-category h3 {
      font-family: var(--mono);
      font-size: 0.9rem;
      color: var(--accent);
      margin-bottom: 1rem;
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }

    .skill-tags {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
    }

    .skill-tag {
      background: rgba(56, 189, 248, 0.08);
      color: var(--text-secondary);
      padding: 0.4rem 0.85rem;
      border-radius: 6px;
      font-size: 0.8rem;
      font-weight: 500;
      border: 1px solid transparent;
      transition: all 0.25s;
    }

    .skill-tag:hover {
      color: var(--accent);
      border-color: var(--accent-dim);
      background: var(--accent-glow);
    }

    /* ── PROJECTS ── */
    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
      gap: 1.5rem;
    }

    .project-card {
      background: var(--bg-card);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 2rem;
      transition: border-color 0.3s, transform 0.3s, box-shadow 0.3s;
      position: relative;
      overflow: hidden;
    }

    .project-card::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      height: 3px;
      background: linear-gradient(90deg, var(--accent), var(--green));
      opacity: 0;
      transition: opacity 0.3s;
    }

    .project-card:hover {
      border-color: var(--accent-dim);
      transform: translateY(-5px);
      box-shadow: 0 16px 48px rgba(0, 0, 0, 0.25);
    }

    .project-card:hover::before { opacity: 1; }

    .project-header {
      display: flex;
      justify-content: space-between;
      align-items: flex-start;
      margin-bottom: 1rem;
    }

    .project-icon {
      font-size: 1.5rem;
      width: 44px;
      height: 44px;
      display: flex;
      align-items: center;
      justify-content: center;
      border-radius: 8px;
      background: var(--accent-glow);
    }

    .project-links { display: flex; gap: 0.75rem; }

    .project-links a {
      color: var(--text-secondary);
      text-decoration: none;
      font-size: 0.85rem;
      transition: color 0.2s;
    }

    .project-links a:hover { color: var(--accent); }

    .project-card h3 {
      font-size: 1.15rem;
      font-weight: 600;
      margin-bottom: 0.5rem;
    }

    .project-card p {
      color: var(--text-secondary);
      font-size: 0.875rem;
      line-height: 1.6;
      margin-bottom: 1.25rem;
    }

    .project-tech {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
    }

    .project-tech span {
      font-family: var(--mono);
      font-size: 0.7rem;
      color: var(--accent);
      background: rgba(56, 189, 248, 0.08);
      padding: 0.3rem 0.65rem;
      border-radius: 4px;
    }

    /* ── CONTACT ── */
    .contact-content {
      text-align: center;
      max-width: 550px;
      margin: 0 auto;
    }

    .contact-content p {
      color: var(--text-secondary);
      font-size: 1.05rem;
      margin-bottom: 2rem;
      line-height: 1.7;
    }

    .social-links {
      display: flex;
      justify-content: center;
      gap: 1rem;
      flex-wrap: wrap;
    }

    .social-link {
      display: inline-flex;
      align-items: center;
      gap: 0.5rem;
      padding: 0.7rem 1.4rem;
      border: 1px solid var(--border);
      border-radius: 8px;
      color: var(--text-secondary);
      text-decoration: none;
      font-size: 0.875rem;
      font-weight: 500;
      transition: all 0.25s;
    }

    .social-link:hover {
      border-color: var(--accent);
      color: var(--accent);
      background: var(--accent-glow);
      transform: translateY(-2px);
    }

    /* ── FOOTER ── */
    footer {
      position: relative;
      z-index: 2;
      text-align: center;
      padding: 2rem;
      font-size: 0.8rem;
      color: var(--text-secondary);
      border-top: 1px solid var(--border);
      font-family: var(--mono);
    }

    /* ── SCROLL ANIMATIONS ── */
    .reveal {
      opacity: 0;
      transform: translateY(30px);
      transition: opacity 0.6s ease-out, transform 0.6s ease-out;
    }

    .reveal.visible {
      opacity: 1;
      transform: translateY(0);
    }

    /* ── MOBILE ── */
    .menu-toggle { display: none; background: none; border: none; cursor: pointer; }

    @media (max-width: 768px) {
      .nav-links {
        display: none;
        flex-direction: column;
        position: absolute;
        top: 100%;
        left: 0;
        right: 0;
        background: rgba(10, 14, 23, 0.95);
        backdrop-filter: blur(16px);
        padding: 1.5rem 2rem;
        gap: 1.25rem;
        border-bottom: 1px solid var(--border);
      }
      .nav-links.open { display: flex; }
      .menu-toggle { display: block; color: var(--text-secondary); font-size: 1.5rem; }
      .about-grid { grid-template-columns: 1fr; }
      section { padding: 4rem 1.25rem; }
    }
  </style>
</head>
<body>

<div id="cursor-glow"></div>

<!-- NAV -->
<nav>
  <div class="nav-logo">&lt;Milan <span>/&gt;</span></div>
  <button class="menu-toggle" onclick="document.querySelector('.nav-links').classList.toggle('open')" aria-label="Menu">☰</button>
  <ul class="nav-links">
    <li><a href="#about">About</a></li>
    <li><a href="#skills">Skills</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</nav>

<!-- HERO -->
<section id="hero">
  <div class="hero-tag">👋 Hello, World!</div>
  <h1 class="hero-name">Milan Varshney</h1>
  <p class="hero-subtitle">Software Developer</p>

  <div class="terminal">
    <div class="terminal-bar">
      <div class="terminal-dot"></div>
      <div class="terminal-dot"></div>
      <div class="terminal-dot"></div>
      <span class="terminal-title">milan@dev ~</span>
    </div>
    <div class="terminal-body">
      <div><span class="prompt">$</span> <span class="cmd">cat about.txt</span></div>
      <div id="typed-output"><span class="cursor"></span></div>
    </div>
  </div>

  <div class="cta-row">
    <a href="#projects" class="btn btn-primary">View Projects ↓</a>
    <a href="https://github.com/Milan-Varshney" target="_blank" class="btn btn-outline">GitHub ↗</a>
  </div>
</section>

<!-- ABOUT -->
<section id="about">
  <div class="reveal">
    <div class="section-label">About Me</div>
    <h2 class="section-title">Building things that matter.</h2>
  </div>
  <div class="about-grid">
    <div class="about-text reveal">
      <p>
        I'm a software developer who enjoys turning complex problems into clean, efficient solutions. I focus on writing code that's not just functional but maintainable and scalable.
      </p>
      <br>
      <p>
        Whether it's building full-stack web apps, crafting APIs, or diving into a new tech stack — I'm driven by curiosity and a commitment to continuous learning. I believe great software starts with understanding the problem deeply before writing a single line of code.
      </p>
    </div>
    <div class="stats-grid reveal">
      <div class="stat-card">
        <div class="stat-number" data-target="10">0+</div>
        <div class="stat-label">Projects Built</div>
      </div>
      <div class="stat-card">
        <div class="stat-number" data-target="5">0+</div>
        <div class="stat-label">Tech Stacks</div>
      </div>
      <div class="stat-card">
        <div class="stat-number" data-target="500">0+</div>
        <div class="stat-label">GitHub Commits</div>
      </div>
      <div class="stat-card">
        <div class="stat-number">∞</div>
        <div class="stat-label">Cups of Coffee</div>
      </div>
    </div>
  </div>
</section>

<!-- SKILLS -->
<section id="skills">
  <div class="reveal">
    <div class="section-label">Tech Stack</div>
    <h2 class="section-title">Tools I work with.</h2>
  </div>
  <div class="skills-container">
    <div class="skill-category reveal">
      <h3>⚡ Languages</h3>
      <div class="skill-tags">
        <span class="skill-tag">JavaScript</span>
        <span class="skill-tag">Python</span>
        <span class="skill-tag">Java</span>
        <span class="skill-tag">C++</span>
        <span class="skill-tag">TypeScript</span>
        <span class="skill-tag">SQL</span>
      </div>
    </div>
    <div class="skill-category reveal">
      <h3>🌐 Frontend</h3>
      <div class="skill-tags">
        <span class="skill-tag">React</span>
        <span class="skill-tag">HTML / CSS</span>
        <span class="skill-tag">Tailwind CSS</span>
        <span class="skill-tag">Next.js</span>
      </div>
    </div>
    <div class="skill-category reveal">
      <h3>🛠️ Backend & Tools</h3>
      <div class="skill-tags">
        <span class="skill-tag">Node.js</span>
        <span class="skill-tag">Express</span>
        <span class="skill-tag">MongoDB</span>
        <span class="skill-tag">Git & GitHub</span>
        <span class="skill-tag">REST APIs</span>
        <span class="skill-tag">Docker</span>
      </div>
    </div>
  </div>
</section>

<!-- PROJECTS -->
<section id="projects">
  <div class="reveal">
    <div class="section-label">Projects</div>
    <h2 class="section-title">Things I've built.</h2>
  </div>
  <div class="projects-grid">

    <div class="project-card reveal">
      <div class="project-header">
        <div class="project-icon">📋</div>
        <div class="project-links">
          <a href="#" target="_blank" title="GitHub">Code ↗</a>
          <a href="#" target="_blank" title="Live">Live ↗</a>
        </div>
      </div>
      <h3>Task Manager App</h3>
      <p>A full-stack task management application with authentication, CRUD operations, and a responsive dashboard.</p>
      <div class="project-tech">
        <span>React</span>
        <span>Node.js</span>
        <span>MongoDB</span>
      </div>
    </div>

    <div class="project-card reveal">
      <div class="project-header">
        <div class="project-icon">💬</div>
        <div class="project-links">
          <a href="#" target="_blank" title="GitHub">Code ↗</a>
          <a href="#" target="_blank" title="Live">Live ↗</a>
        </div>
      </div>
      <h3>Real-time Chat App</h3>
      <p>WebSocket-powered chat application supporting rooms, typing indicators, and message persistence.</p>
      <div class="project-tech">
        <span>Socket.io</span>
        <span>Express</span>
        <span>React</span>
      </div>
    </div>

    <div class="project-card reveal">
      <div class="project-header">
        <div class="project-icon">🌤️</div>
        <div class="project-links">
          <a href="#" target="_blank" title="GitHub">Code ↗</a>
          <a href="#" target="_blank" title="Live">Live ↗</a>
        </div>
      </div>
      <h3>Weather Dashboard</h3>
      <p>Location-based weather dashboard with 5-day forecast, interactive charts, and dark/light themes.</p>
      <div class="project-tech">
        <span>JavaScript</span>
        <span>REST API</span>
        <span>Chart.js</span>
      </div>
    </div>

  </div>
</section>

<!-- CONTACT -->
<section id="contact">
  <div class="reveal contact-content">
    <div class="section-label" style="justify-content:center">Get In Touch</div>
    <h2 class="section-title">Let's connect.</h2>
    <p>I'm always open to discussing new projects, ideas, or opportunities. Feel free to reach out!</p>
    <div class="social-links">
      <a href="mailto:your.email@example.com" class="social-link">✉️ Email</a>
      <a href="https://github.com/Milan-Varshney" target="_blank" class="social-link">💻 GitHub</a>
      <a href="https://linkedin.com/in/your-linkedin" target="_blank" class="social-link">🔗 LinkedIn</a>
    </div>
  </div>
</section>

<footer>
  &lt;/&gt; built with ☕ by Milan Varshney
</footer>

<script>
  // ── Cursor glow ──
  const glow = document.getElementById('cursor-glow');
  document.addEventListener('mousemove', e => {
    glow.style.left = e.clientX + 'px';
    glow.style.top = e.clientY + 'px';
  });

  // ── Typing animation ──
  const lines = [
    { text: '> Passionate about building clean, scalable software.', cls: 'output' },
    { text: '> Exploring full-stack development & open source.', cls: 'highlight' },
    { text: '> Currently looking for exciting opportunities!', cls: 'output' },
  ];

  const typedOutput = document.getElementById('typed-output');
  let lineIdx = 0, charIdx = 0;

  function typeWriter() {
    if (lineIdx >= lines.length) return;
    const line = lines[lineIdx];
    if (charIdx === 0) {
      const span = document.createElement('div');
      span.className = line.cls;
      span.id = 'line-' + lineIdx;
      typedOutput.insertBefore(span, typedOutput.lastElementChild);
    }
    const el = document.getElementById('line-' + lineIdx);
    el.textContent = line.text.substring(0, charIdx + 1);
    charIdx++;
    if (charIdx < line.text.length) {
      setTimeout(typeWriter, 28);
    } else {
      charIdx = 0;
      lineIdx++;
      setTimeout(typeWriter, 400);
    }
  }

  setTimeout(typeWriter, 800);

  // ── Scroll reveal ──
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(e => { if (e.isIntersecting) e.target.classList.add('visible'); });
  }, { threshold: 0.15 });

  document.querySelectorAll('.reveal').forEach(el => observer.observe(el));

  // ── Stat counter animation ──
  const statObserver = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (!entry.isIntersecting) return;
      const el = entry.target;
      const target = parseInt(el.dataset.target);
      if (!target) return;
      let current = 0;
      const step = Math.max(1, Math.floor(target / 40));
      const interval = setInterval(() => {
        current += step;
        if (current >= target) { current = target; clearInterval(interval); }
        el.textContent = current + '+';
      }, 30);
      statObserver.unobserve(el);
    });
  }, { threshold: 0.5 });

  document.querySelectorAll('.stat-number[data-target]').forEach(el => statObserver.observe(el));

  // ── Close mobile menu on link click ──
  document.querySelectorAll('.nav-links a').forEach(a => {
    a.addEventListener('click', () => document.querySelector('.nav-links').classList.remove('open'));
  });
</script>
</body>
</html>
