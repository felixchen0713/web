---
title: ""
hideMeta: true
showToc: false
---

<div class="home-grid">

  <!-- Left sidebar -->
  <aside class="home-sidebar">

    <div class="card">
      <img class="avatar" src="/images/felix.jpg" alt="Xiaoxing Chen" />
      <h2 class="name">Xiaoxing Chen</h2>
      <p class="subtitle">
        CS Graduate student focusing on security @ Duke University
      </p>

      <div class="quick-links">
        <a class="btn" href="/about/">About me</a>
        <a class="btn" href="/projects/">Projects</a>
        <a class="btn" href="/cv/">CV / Resume</a>
      </div>
    </div>

    <div class="card">
      <h3>Contact</h3>
      <ul class="list">
        <li>🔗 <a href="https://www.linkedin.com/in/xiaoxing-chen-8448b7263/" target="_blank" rel="noopener">LinkedIn</a></li>
        <li>💻 <a href="https://github.com/felixchen0713" target="_blank" rel="noopener">GitHub</a></li>
        <li>📄 <a href="/images/Resume.pdf" target="_blank" rel="noopener">Resume PDF</a></li>
      </ul>
    </div>

    <div class="card">
      <h3>Cat</h3>
      <div class="mini">
        <img class="miniimg" src="/images/cat.jpg" alt="cat" />
        <p class="minitxt">My roommate’s cat 🐾</p>
      </div>
    </div>

  </aside>

  <!-- Right main -->
  <main class="home-main">
    <h1 class="headline">Hi, I’m Xiaoxing.</h1>
    <p class="lead">
      I’m a CS graduate student focusing on security at Duke University.
      I like building practical systems and turning ideas into working prototypes.
    </p>

    <h2 class="section-title">Key Highlights</h2>

    <div class="stats">
      <div class="statcard">
        <h3>Security</h3>
        <p>Network security, threat detection, secure system design.</p>
      </div>
      <div class="statcard">
        <h3>Systems</h3>
        <p>Distributed systems, reliability, debugging, performance.</p>
      </div>
      <div class="statcard">
        <h3>Projects</h3>
        <p>CRDT collaborative editor, security labs, data pipelines.</p>
      </div>
      <div class="statcard">
        <h3>Open to</h3>
        <p>Security / SWE internships & entry-level roles.</p>
      </div>
    </div>

    <h2 class="section-title">Quick Links</h2>
    <ul>
      <li><a href="/about/">About</a></li>
      <li><a href="/projects/">Projects</a></li>
      <li><a href="/publications/">Publications</a></li>
      <li><a href="/research/">Research</a></li>
      <li><a href="/teaching/">Teaching</a></li>
      <li><a href="/posts/">Blog</a></li>
    </ul>
  </main>

</div>

<style>
.home-grid {
  display: grid;
  grid-template-columns: 320px 1fr;
  gap: 24px;
  align-items: start;
}

@media (max-width: 900px) {
  .home-grid { grid-template-columns: 1fr; }
}

.home-sidebar .card,
.home-main .statcard {
  border: 1px solid var(--border);
  border-radius: 14px;
  padding: 16px;
  background: var(--entry);
}

.avatar {
  width: 100%;
  border-radius: 14px;
  display: block;
}

.name { margin: 12px 0 4px; }
.subtitle {
  margin: 0 0 12px;
  color: var(--secondary);
  line-height: 1.35;
}

.quick-links {
  display: grid;
  gap: 10px;
  margin-top: 10px;
}

.btn {
  display: inline-block;
  padding: 10px 12px;
  border-radius: 12px;
  border: 1px solid var(--border);
  text-align: center;
  text-decoration: none;
}

.list { margin: 8px 0 0; padding-left: 18px; }

.headline { margin-top: 0; }
.lead {
  color: var(--secondary);
  font-size: 1.05rem;
  line-height: 1.6;
}

.section-title { margin-top: 28px; }

.stats {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 14px;
}

@media (max-width: 900px) {
  .stats { grid-template-columns: 1fr; }
}

.statcard h3 { margin: 0 0 6px; }

.mini {
  display: grid;
  grid-template-columns: 80px 1fr;
  gap: 12px;
  align-items: center;
}

.miniimg {
  width: 80px;
  height: 80px;
  object-fit: cover;
  border-radius: 12px;
  border: 1px solid var(--border);
}

.minitxt { margin: 0; color: var(--secondary); }
</style>
