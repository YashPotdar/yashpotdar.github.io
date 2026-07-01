---
layout: null
---

<style>
  :root {
    color-scheme: dark;
  }

  html, body {
    margin: 0;
    padding: 0;
    background: linear-gradient(135deg, #07111f 0%, #0f172a 100%);
    color: #e2e8f0;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
  }

  * { box-sizing: border-box; }

  a {
    color: #8ec5ff;
    text-decoration: none;
  }

  a:hover {
    text-decoration: underline;
  }

  .container {
    max-width: 1040px;
    margin: 0 auto;
    padding: 72px 24px 88px;
  }

  .top-links {
    display: flex;
    justify-content: flex-end;
    gap: 14px;
    margin-bottom: 18px;
    font-size: 0.95rem;
  }

  .hero {
    padding: 24px 0 24px;
  }

  .eyebrow {
    display: inline-block;
    font-size: 12px;
    letter-spacing: 0.18em;
    text-transform: uppercase;
    color: #7dd3fc;
    margin-bottom: 14px;
  }

  .title {
    font-size: clamp(2.3rem, 5vw, 3.6rem);
    font-weight: 800;
    line-height: 1.05;
    margin: 0 0 12px;
    letter-spacing: -0.03em;
  }

  .lead {
    font-size: 1.05rem;
    line-height: 1.75;
    color: #cbd5e1;
    max-width: 720px;
    margin: 0 0 22px;
  }

  .cta-row {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
    margin-bottom: 20px;
  }

  .btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    padding: 10px 16px;
    border-radius: 999px;
    font-size: 0.95rem;
    font-weight: 600;
    transition: transform 0.2s ease, border-color 0.2s ease;
  }

  .btn:hover {
    transform: translateY(-2px);
    text-decoration: none;
  }

  .btn-primary {
    background: linear-gradient(135deg, #3b82f6, #2563eb);
    color: white;
  }

  .pill-row {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 6px;
  }

  .pill {
    display: inline-block;
    padding: 7px 11px;
    border-radius: 999px;
    background: rgba(125, 211, 252, 0.14);
    color: #bae6fd;
    font-size: 0.85rem;
  }

  .section {
    margin-top: 44px;
  }

  .section-title {
    font-size: 0.9rem;
    letter-spacing: 0.16em;
    text-transform: uppercase;
    color: #94a3b8;
    margin-bottom: 16px;
  }

  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 16px;
  }

  .card {
    background: rgba(15, 23, 42, 0.8);
    border: 1px solid rgba(148, 163, 184, 0.18);
    border-radius: 16px;
    padding: 18px;
    box-shadow: 0 12px 30px rgba(2, 6, 23, 0.16);
    transition: transform 0.2s ease, border-color 0.2s ease;
  }

  .card:hover {
    transform: translateY(-4px);
    border-color: rgba(96, 165, 250, 0.6);
  }

  .badge {
    display: inline-block;
    font-size: 0.72rem;
    padding: 5px 10px;
    border-radius: 999px;
    background: rgba(59, 130, 246, 0.16);
    color: #93c5fd;
    margin-bottom: 10px;
  }

  .card h3 {
    margin: 0 0 8px;
    font-size: 1.05rem;
  }

  .card p {
    margin: 0;
    color: #cbd5e1;
    font-size: 0.95rem;
    line-height: 1.6;
  }

  .links {
    margin-top: 12px;
    font-size: 0.9rem;
  }

  .footer {
    margin-top: 52px;
    font-size: 0.9rem;
    color: #94a3b8;
  }

  @media (max-width: 640px) {
    .container { padding: 56px 18px 72px; }
    .lead { font-size: 1rem; }
  }
</style>

<div class="container">
  <div class="top-links">
    <a href="https://github.com/YashPotdar" target="_blank">GitHub</a>
    <a href="https://www.linkedin.com/in/yashmpotdar" target="_blank">LinkedIn</a>
  </div>

  <section class="hero">
    <div class="eyebrow">Software engineer • applied AI</div>
    <h1 class="title">Yash Potdar</h1>
    <p class="lead">
      Customer-obsessed software engineer with full-stack expertise, proven track record delivering production systems at scale for both enterprise and startup environments.
    </p>

    <div class="cta-row">
      <a class="btn btn-primary" href="https://yashpotdar.dev">Full Portfolio →</a>
    </div>

    <div class="pill-row">
      <span class="pill">Software engineering</span>
      <span class="pill">ML systems</span>
      <span class="pill">Applied AI</span>
      <span class="pill">Product design</span>
      <span class="pill">Research</span>
    </div>
  </section>

  <section class="section">
    <h2 class="section-title">Selected work</h2>
    <div class="grid">
      <div class="card">
        <div class="badge">ML / research</div>
        <h3>Pulmonary Edema Detection</h3>
        <p>A medical imaging project using CNNs and clinical features to support pulmonary edema classification.</p>
        <div class="links">
          <a href="https://yashpotdar.github.io/deep-learning-pulmonary-edema/">Open project →</a>
        </div>
      </div>

      <div class="card">
        <div class="badge">UI / product</div>
        <h3>Facebook Redesign</h3>
        <p>A modern UI exploration focused on clarity, hierarchy, and a more engaging feed experience.</p>
        <div class="links">
          <a href="https://yashpotdar.github.io/facebook-redesign/">Open project →</a>
        </div>
      </div>
    </div>
  </section>

  <section class="section">
    <h2 class="section-title">Currently</h2>
    <div class="card">
      <p>Working at the intersection of AI, health tech, and product design, with a focus on practical systems and meaningful user outcomes.</p>
    </div>
  </section>

  <div class="footer">
    Built with Jekyll and GitHub Pages • Portfolio at
    <a href="https://yashpotdar.dev">yashpotdar.dev</a>
  </div>
</div>
