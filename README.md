
<style>
@import url('https://fonts.googleapis.com/css2?family=DM+Mono:wght@400;500&family=Syne:wght@400;500;700&display=swap');

* { box-sizing: border-box; margin: 0; padding: 0; }

body { font-family: 'Syne', sans-serif; }

.container {
  max-width: 780px;
  padding: 2.5rem 2rem;
  color: var(--color-text-primary);
}

.header {
  border-left: 2px solid var(--color-text-primary);
  padding-left: 1.25rem;
  margin-bottom: 2.5rem;
}

.header .name {
  font-size: 28px;
  font-weight: 700;
  letter-spacing: -0.5px;
  line-height: 1.1;
}

.header .role {
  font-size: 13px;
  font-family: 'DM Mono', monospace;
  color: var(--color-text-secondary);
  margin-top: 6px;
  letter-spacing: 0.5px;
}

.school-badge {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  margin-top: 12px;
  font-size: 12px;
  font-family: 'DM Mono', monospace;
  color: var(--color-text-secondary);
  background: var(--color-background-secondary);
  border: 0.5px solid var(--color-border-tertiary);
  border-radius: var(--border-radius-md);
  padding: 4px 10px;
}

.dot {
  width: 6px; height: 6px;
  border-radius: 50%;
  background: #1D9E75;
}

.bio {
  font-size: 15px;
  line-height: 1.75;
  color: var(--color-text-secondary);
  margin-bottom: 2.5rem;
  max-width: 600px;
}

.bio strong {
  color: var(--color-text-primary);
  font-weight: 500;
}

.section-label {
  font-size: 11px;
  font-family: 'DM Mono', monospace;
  letter-spacing: 1.5px;
  text-transform: uppercase;
  color: var(--color-text-tertiary);
  margin-bottom: 1rem;
}

.stack-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(160px, 1fr));
  gap: 10px;
  margin-bottom: 2.5rem;
}

.stack-card {
  background: var(--color-background-secondary);
  border: 0.5px solid var(--color-border-tertiary);
  border-radius: var(--border-radius-lg);
  padding: 14px 16px;
}

.stack-card .cat {
  font-size: 11px;
  font-family: 'DM Mono', monospace;
  color: var(--color-text-tertiary);
  margin-bottom: 6px;
}

.stack-card .items {
  font-size: 13px;
  color: var(--color-text-primary);
  font-weight: 500;
  line-height: 1.6;
}

.projects {
  margin-bottom: 2.5rem;
}

.project-row {
  display: flex;
  align-items: baseline;
  gap: 12px;
  padding: 10px 0;
  border-bottom: 0.5px solid var(--color-border-tertiary);
}

.project-row:first-child {
  border-top: 0.5px solid var(--color-border-tertiary);
}

.project-arrow {
  font-family: 'DM Mono', monospace;
  font-size: 12px;
  color: var(--color-text-tertiary);
  flex-shrink: 0;
}

.project-name {
  font-size: 14px;
  font-weight: 500;
  color: var(--color-text-primary);
  flex-shrink: 0;
  min-width: 180px;
}

.project-desc {
  font-size: 13px;
  color: var(--color-text-secondary);
  font-family: 'DM Mono', monospace;
}

.focus-block {
  border-left: 2px solid #1D9E75;
  padding-left: 1.25rem;
}

.focus-block p {
  font-size: 14px;
  line-height: 1.7;
  color: var(--color-text-secondary);
}

.focus-block p strong {
  color: var(--color-text-primary);
  font-weight: 500;
}

.tagline {
  margin-top: 2.5rem;
  padding-top: 1.5rem;
  border-top: 0.5px solid var(--color-border-tertiary);
  font-size: 13px;
  font-family: 'DM Mono', monospace;
  color: var(--color-text-tertiary);
  letter-spacing: 0.3px;
}
</style>

<div class="container">

  <div class="header">
    <div class="name">Mohamed Badr Elwardi</div>
    <div class="role">full-stack web developer</div>
    <div class="school-badge">
      <span class="dot"></span>
      1337 Coding School · 42 Network
    </div>
  </div>

  <p class="bio">
    Software engineering student with a foundation in <strong>system programming, algorithms, and software architecture</strong>. My journey started with raw C pointers, memory, and algorithms. That background shapes how I think, but <strong>full-stack web development</strong> is where my passion lives.
  </p>

  <div class="section-label">stack</div>
  <div class="stack-grid">
    <div class="stack-card">
      <div class="cat">languages</div>
      <div class="items">C / C++<br>JavaScript<br>TypeScript</div>
    </div>
    <div class="stack-card">
      <div class="cat">web</div>
      <div class="items">React<br>Next.js<br>Node.js</div>
    </div>
    <div class="stack-card">
      <div class="cat">backend</div>
      <div class="items">REST APIs<br>Auth systems<br>Databases</div>
    </div>
    <div class="stack-card">
      <div class="cat">tools</div>
      <div class="items">Git<br>Linux<br>Docker</div>
    </div>
  </div>

  <div class="section-label">projects</div>
  <div class="projects">
    <div class="project-row">
      <span class="project-arrow">→</span>
      <span class="project-name">Full-stack web apps</span>
      <span class="project-desc">end-to-end applications</span>
    </div>
    <div class="project-row">
      <span class="project-arrow">→</span>
      <span class="project-name">HTTP server</span>
      <span class="project-desc">built from scratch in C++</span>
    </div>
    <div class="project-row">
      <span class="project-arrow">→</span>
      <span class="project-name">Raycasting engine</span>
      <span class="project-desc">C++ graphics renderer</span>
    </div>
    <div class="project-row">
      <span class="project-arrow">→</span>
      <span class="project-name">C libraries & utilities</span>
      <span class="project-desc">low-level system tools</span>
    </div>
  </div>

  <div class="section-label">currently</div>
  <div class="focus-block">
    <p>Going all in on <strong>full-stack web development</strong> deepening my skills, taking on bigger challenges, and building things that matter. Every project is a chance to grow.</p>
  </div>

  <div class="tagline">// i love the daily challenge of building real applications. that's the point.</div>

</div>
