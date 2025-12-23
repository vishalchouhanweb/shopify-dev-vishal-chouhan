<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Vishal Chouhan | Shopify Developer</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>

<!-- NAV -->
<header class="nav">
  <div class="nav-inner">
    <strong>Vishal.dev</strong>
    <a href="mailto:vishalrajputt88@gmail.com" class="nav-btn">Hire Me</a>
  </div>
</header>

<!-- HERO -->
<section class="hero">
  <div class="hero-inner">

    <div class="hero-text">
      <span class="badge">Shopify Expert</span>
      <h1>Building High-Performance<br>Shopify Stores</h1>
      <p>
        3.5+ years experience • 100+ Shopify stores • Custom themes • APIs • Speed
      </p>

      <div class="hero-actions">
        <a href="mailto:vishalrajputt88@gmail.com" class="btn primary">Hire Me</a>
        <a href="https://linkedin.com/in/vishal-chouhan-shopify-dev" target="_blank" class="btn ghost">LinkedIn</a>
      </div>
    </div>

    <div class="hero-profile">
      <img src="https://media.licdn.com/dms/image/v2/D4D35AQFTQ4fQTmNXvA/profile-framedphoto-shrink_200_200/B4DZktdeYJJMAY-/0/1757404325747?e=1767088800&v=beta&t=MyNBvnHUtlGDIP6mtCjXLcBVcDv8yxrLoS7-W5tSVh4" alt="Vishal"/>
    </div>

  </div>
</section>

<!-- STATS -->
<section class="stats">
  <div class="stat"><strong>100+</strong><span>Shopify Stores</span></div>
  <div class="stat"><strong>3.5+</strong><span>Years Experience</span></div>
  <div class="stat"><strong>20+</strong><span>Custom Apps</span></div>
</section>

<!-- SKILLS -->
<section class="section">
  <h2>What I Do</h2>

  <div class="grid">
    <div class="card">Custom Shopify Themes</div>
    <div class="card">Shopify 2.0 Sections</div>
    <div class="card">Liquid & Metafields</div>
    <div class="card">API Integrations</div>
    <div class="card">Speed Optimization</div>
    <div class="card">UI / UX from Figma</div>
  </div>
</section>

<!-- EXPERIENCE -->
<section class="section dark">
  <h2>Experience</h2>

  <div class="experience">
    <h3>Shopify Developer — Ninja Technology</h3>
    <small>May 2021 – Oct 2024</small>

    <ul>
      <li>Built 100+ Shopify stores (custom + premium themes)</li>
      <li>Advanced Liquid logic & schema-based sections</li>
      <li>Shopify APIs, metafields, checkout flows</li>
      <li>Speed optimization & mobile UI fixes</li>
    </ul>
  </div>
</section>

<!-- PROJECTS -->
<section class="section">
  <h2>Selected Projects</h2>

  <div class="projects">
    <div class="project">Metics Fashion</div>
    <div class="project">ATVEL</div>
    <div class="project">NYX Cosmetics India</div>
    <div class="project">With Clarity</div>
    <div class="project">Spacemilk</div>
    <div class="project">Omaha Sheriff</div>
  </div>
</section>

<!-- CTA -->
<section class="cta">
  <h2>Need a Shopify Expert?</h2>
  <p>Available for freelance & full-time roles</p>
  <a href="mailto:vishalrajputt88@gmail.com" class="btn primary">Let’s Talk</a>
</section>

<!-- FOOTER -->
<footer>
  <p>📍 Indore, India • 📞 9977999178 • ✉️ vishalrajputt88@gmail.com</p>
</footer>

</body>
<style>
:root {
  --green: #22c55e;
  --dark: #0f172a;
  --darker: #020617;
  --border: #1e293b;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: system-ui, -apple-system, sans-serif;
}

body {
  background: var(--dark);
  color: #e5e7eb;
  line-height: 1.6;
}

/* NAV */
.nav {
  background: #020617;
  border-bottom: 1px solid var(--border);
}
.nav-inner {
  max-width: 1100px;
  margin: auto;
  padding: 15px 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.nav-btn {
  color: var(--green);
  text-decoration: none;
  font-weight: 600;
}

/* HERO */
.hero {
  padding: 80px 20px;
}
.hero-inner {
  max-width: 1100px;
  margin: auto;
  display: grid;
  grid-template-columns: 1.2fr 1fr;
  gap: 40px;
  align-items: center;
}
.badge {
  display: inline-block;
  background: rgba(34,197,94,.15);
  color: var(--green);
  padding: 6px 12px;
  border-radius: 20px;
  font-size: 14px;
  margin-bottom: 15px;
}
.hero h1 {
  font-size: 44px;
  line-height: 1.2;
}
.hero p {
  margin: 20px 0;
  color: #cbd5f5;
}
.hero-profile img {
  width: 260px;
  height: 260px;
  object-fit: cover;
  border-radius: 50%;
  border: 4px solid var(--green);
}

/* BUTTONS */
.btn {
  padding: 12px 22px;
  border-radius: 8px;
  text-decoration: none;
  font-weight: 600;
}
.primary {
  background: var(--green);
  color: #022c22;
}
.ghost {
  border: 2px solid var(--green);
  color: var(--green);
  margin-left: 10px;
}

/* STATS */
.stats {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px,1fr));
  max-width: 1100px;
  margin: 0 auto 60px;
  border-top: 1px solid var(--border);
  border-bottom: 1px solid var(--border);
}
.stat {
  padding: 30px;
  text-align: center;
}
.stat strong {
  font-size: 32px;
  color: var(--green);
}

/* SECTIONS */
.section {
  padding: 70px 20px;
  max-width: 1100px;
  margin: auto;
}
.section h2 {
  text-align: center;
  font-size: 32px;
  margin-bottom: 40px;
}
.section.dark {
  background: var(--darker);
}

/* GRID */
.grid, .projects {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px,1fr));
  gap: 20px;
}
.card, .project {
  background: var(--darker);
  padding: 30px;
  border-radius: 12px;
  border: 1px solid var(--border);
  text-align: center;
  font-weight: 600;
}

/* EXPERIENCE */
.experience {
  max-width: 700px;
  margin: auto;
}
.experience small {
  color: #9ca3af;
}
.experience ul {
  margin-top: 20px;
  padding-left: 20px;
}

/* CTA */
.cta {
  padding: 80px 20px;
  background: linear-gradient(135deg, #022c22, #052e16);
  text-align: center;
}
.cta h2 {
  font-size: 36px;
}
.cta p {
  margin: 15px 0 25px;
}

/* FOOTER */
footer {
  text-align: center;
  padding: 30px;
  background: var(--darker);
  color: #9ca3af;
}

/* RESPONSIVE */
@media(max-width:768px){
  .hero-inner{
    grid-template-columns: 1fr;
    text-align:center;
  }
  .hero-profile img{
    margin:auto;
  }
}

  
</style>


</html>
