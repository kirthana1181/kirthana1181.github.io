<style>
:root {
  --primary: #4f46e5;
  --secondary: #6366f1;
  --accent: #22c55e;
  --bg: #f8fafc;
  --text: #111827;
  --muted: #6b7280;
  --card: #ffffff;
  --border: #e5e7eb;
  --radius: 14px;
  --gap: 1rem;
}

/* Use the full available content width of the page. */
.portfolio-shell {
  width: calc(100vw - 3rem);
  max-width: none;
  margin-left: calc(50% - 50vw + 1.5rem);
  margin-right: 0;
  padding: 0.75rem 0 1.5rem;
  box-sizing: border-box;
}

.portfolio-shell section {
  margin: 0 0 var(--gap);
}

.portfolio-shell section:last-child {
  margin-bottom: 0;
}

.portfolio-shell h1,
.portfolio-shell h2,
.portfolio-shell h3 {
  font-weight: 700;
  letter-spacing: -0.02em;
}

.portfolio-shell h1 {
  font-size: 2.25rem;
  line-height: 1.15;
  margin: 0 0 0.35rem;
}

.portfolio-shell h2 {
  color: var(--secondary);
  font-size: 1.3rem;
  line-height: 1.25;
  margin: 0 0 0.8rem;
}

.portfolio-shell h3 {
  font-size: 1.05rem;
  line-height: 1.3;
  margin: 0 0 0.3rem;
}

.portfolio-shell p {
  margin: 0.45rem 0;
}

/* Shared card treatment */
.card,
.hero-card,
.cta-card,
.proof-item {
  width: 100%;
  background: var(--card);
  border-radius: var(--radius);
  box-shadow: 0 6px 18px rgba(0, 0, 0, 0.05);
  box-sizing: border-box;
}

.card {
  height: 100%;
  padding: 1.2rem 1.35rem;
  border: 1px solid var(--border);
}

.hero-card {
  padding: 1.75rem 2rem;
  border: 2px solid var(--primary);
}

.profile-container {
  display: flex;
  align-items: center;
  gap: 2rem;
  text-align: left;
}

.profile-image {
  flex: 0 0 auto;
}

.profile-image img {
  display: block;
  width: 135px;
  height: 135px;
  border: 0;
  border-radius: 50%;
  object-fit: cover;
  box-shadow: none;
}

.profile-text {
  flex: 1 1 auto;
  min-width: 0;
}

.hero-role {
  color: var(--secondary);
  font-size: 1.06rem;
  font-weight: 650;
  margin: 0 0 0.5rem;
}

.focus-chips,
.opportunity-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.45rem;
  margin-top: 0.75rem;
}

.focus-chip,
.opportunity-tag {
  padding: 0.3rem 0.7rem;
  border: 1px solid #c7d2fe;
  border-radius: 999px;
  background: #eef2ff;
  color: #3730a3;
  font-size: 0.82rem;
  font-weight: 600;
}

.hero-actions {
  display: flex;
  flex-wrap: wrap;
  gap: 0.6rem;
  margin-top: 0.9rem;
}

.button {
  display: inline-block;
  padding: 0.52rem 0.9rem;
  border-radius: 8px;
  background: var(--primary);
  color: #fff !important;
  font-size: 0.88rem;
  font-weight: 650;
  line-height: 1.2;
  text-decoration: none !important;
}

.button.secondary {
  background: #eef2ff;
  color: #3730a3 !important;
  border: 1px solid #c7d2fe;
}

/* Top welcome + opportunities cards */
.top-cards {
  display: grid;
  grid-template-columns: minmax(0, 2fr) minmax(360px, 1fr);
  gap: var(--gap);
  align-items: stretch;
}

.top-cards > section {
  margin: 0;
  min-width: 0;
}

.top-cards .hero-card,
.top-cards .cta-card {
  height: 100%;
}

/* Three equal highlight cards. */
.proof-bar {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: var(--gap);
}

.proof-item {
  min-height: 88px;
  padding: 0.8rem 0.9rem;
  border: 1px solid var(--border);
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: center;
}

.proof-item strong {
  display: block;
  color: var(--primary);
  font-size: 0.92rem;
  line-height: 1.25;
}

.proof-item span {
  display: block;
  color: var(--muted);
  font-size: 0.77rem;
  line-height: 1.35;
  margin-top: 0.2rem;
}

/* Full-width content cards. */
.two-column {
  display: grid;
  grid-template-columns: 1fr;
  gap: var(--gap);
  align-items: stretch;
}

.two-column > .card {
  width: 100%;
}

.project-preview + .project-preview {
  margin-top: 0.85rem;
  padding-top: 0.85rem;
  border-top: 1px solid var(--border);
}

.project-preview p {
  margin: 0.25rem 0 0;
}

.text-link {
  font-weight: 650;
}

/* Experience card */
.experience-item + .experience-item {
  margin-top: 0.85rem;
  padding-top: 0.85rem;
  border-top: 1px solid var(--border);
}

.experience-item h3 {
  margin: 0 0 0.18rem;
  font-size: 1rem;
}

.experience-item p {
  margin: 0.22rem 0;
  font-size: 0.88rem;
}

.experience-date {
  color: var(--muted);
  font-size: 0.78rem !important;
  font-weight: 600;
}

.experience-skills {
  display: flex;
  flex-wrap: wrap;
  gap: 0.35rem;
  margin-top: 0.5rem;
}

.experience-tag {
  display: inline-block;
  padding: 0.24rem 0.58rem;
  border: 1px solid #c7d2fe;
  border-radius: 999px;
  background: #eef2ff;
  color: #3730a3;
  font-size: 0.74rem;
  line-height: 1.25;
  font-weight: 600;
}

.compact-list {
  margin: 0.4rem 0 0;
  padding-left: 1.15rem;
}

.compact-list li {
  margin-bottom: 0.25rem;
}

/* CTA */
.cta-card {
  padding: 1.15rem 1.35rem;
  border: 1px solid var(--border);
  border-left: 4px solid var(--accent);
}

.cta-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 1.25rem;
  height: 100%;
}

.socials {
  display: flex;
  flex: 0 0 auto;
  gap: 0.6rem;
  align-self: flex-end;
}

.socials a {
  display: inline-flex;
  align-items: center;
  justify-content: center;
}

.socials img {
  display: block;
  width: 27px;
  height: 27px;
  filter: grayscale(1);
  transition: transform 0.2s ease, filter 0.2s ease;
}

.socials img:hover {
  filter: grayscale(0);
  transform: translateY(-2px);
}

.masthead__menu-item a {
  color: #4f46e5 !important;
}

/* Tablet / mobile */
@media (max-width: 900px) {
  .portfolio-shell {
    width: calc(100vw - 2rem);
    margin-left: calc(50% - 50vw + 1rem);
  }

  .hero-card {
    padding: 1.5rem;
  }

  .top-cards {
    grid-template-columns: 1fr;
  }

  .two-column {
    grid-template-columns: minmax(0, 1fr);
  }
}

@media (max-width: 650px) {
  .portfolio-shell {
    width: calc(100vw - 1rem);
    margin-left: calc(50% - 50vw + 0.5rem);
    padding-top: 0.25rem;
  }

  .profile-container {
    flex-direction: column;
    align-items: flex-start;
    gap: 1rem;
  }

  .profile-image img {
    width: 105px;
    height: 105px;
  }

  .portfolio-shell h1 {
    font-size: 1.9rem;
  }

  .proof-bar {
    grid-template-columns: 1fr;
  }

  .proof-item {
    min-height: 0;
    padding: 0.75rem 0.9rem;
  }

  .cta-content {
    flex-direction: column;
    align-items: flex-start;
  }

  .socials {
    align-self: flex-start;
    margin-top: 0.15rem;
  }
}
</style>

<div class="portfolio-shell">
  <div class="top-cards">
  <section>
    <div class="hero-card">
      <div class="profile-container">
        <div class="profile-image">
          <img src="/assets/images/profile.jpg" alt="Profile photo of Kirthana">
        </div>

<div class="profile-text">
  <h1>Hi, I'm Kirthana</h1>
  <p class="hero-role">Pre-Doctoral Fellow</p>
  <p>
    At the Future Computing Systems (FIST) Research Group, Dept. of CSA, IISc. With interests in VLSI and Full-stack AI Hardware Design.
  </p>

  <div class="hero-actions">
    <a class="button" href="/projects">View Projects</a>
    <a class="button secondary" href="/assets/docs/KIRTHANA P RAO_CV1.pdf" download>Download CV</a>
    <a class="button secondary" href="/contact.html">Contact Me</a>
  </div>
</div>

  </div>
</div>

  </section>

<section>
<div class="cta-card">
  <div class="cta-content">
    <div>
      <h2>Open to Opportunities</h2>
      <p>Seeking internships, research roles and collaborations in VLSI, FPGA, AI Hardware and Embedded System Design.</p>
      <div class="opportunity-tags">
        <span class="opportunity-tag">VLSI Design and Computer Architecture</span>
        <span class="opportunity-tag">Embedded Software</span>
        <span class="opportunity-tag">AI Acceleration</span>
      </div>
    </div>

<div class="socials" aria-label="Contact links">
  <a href="https://www.linkedin.com/in/kirthana-p-6b89b326b/" aria-label="LinkedIn">
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/linkedin.svg" alt="">
  </a>
  <a href="https://github.com/kirthana1181" aria-label="GitHub">
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/github.svg" alt="">
  </a>
  <a href="mailto:work.kirthana@gmail.com" aria-label="Email">
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/gmail.svg" alt="">
  </a>
</div>

  </div>
</div>

  </section>
  </div>

  <section aria-label="Highlights and achievements">
    <div class="proof-bar">
      <div class="proof-item">
        <strong>Samsung ISWDP</strong>
        <span>Semiconductor Fellowship Recipient</span>
      </div>

  <div class="proof-item">
    <strong>RoboRythm</strong>
    <span>Second Runner-Up at SOLASTA 2K24</span>
  </div>

  <div class="proof-item">
    <strong>SPARKS</strong>
    <span>Predoctoral Fellowship Recipient, IISc 2026</span>
  </div>
</div>

  </section>

  <section class="two-column">
    <div class="card">
      <h2>Featured Work</h2>

  <div class="project-preview">
    <h3>Compressor-Based Dadda Multiplier</h3>
    <p>Improved speed by <strong>16%</strong> and reduced power by <strong>8%</strong> using optimized compressor logic.</p>
  </div>

  <div class="project-preview">
    <h3>RISC-V Pipelined Processor</h3>
    <p>Implemented a pipelined processor with instruction decoding, register operations and hazard handling.</p>
  </div>

  <p><a class="text-link" href="/projects"><strong>View all projects</strong></a></p>
</div>

<div class="card">
  <h2>Technical Toolkit</h2>
  <p><strong>Hardware:</strong> Verilog HDL, TL-Verilog HDL, FPGA, RTL, RISC-V.</p>
  <p><strong>Software:</strong> Python, C, C++, TensorFlow.</p>
  <p><strong>Tools:</strong> Vivado, Virtuoso, OpenLANE, KiCad, Git, Linux.</p>
  <p><a class="text-link" href="/skills"><strong>Explore skills</strong></a></p>
</div>

  </section>

  <section>
    <div class="card">
      <h2>Experience</h2>

  <div class="experience-item">
    <h3>Research Intern, IISc Bangalore</h3>
    <p class="experience-date">Jan 2026 - July 2026</p>
    <p>
      Worked on developing an end-to-end implementation framework for deploying ML Algorithms on FPGAs, as part of an industry project at the Future Computing Systems (FIST) Research group, at the Dept. of Computer Science &amp; Automation.
    </p>
    <div class="experience-skills">
      <span class="experience-tag">Verilog</span>
      <span class="experience-tag">Machine Learning</span>
      <span class="experience-tag">FINN Compiler</span>
      <span class="experience-tag">RTL Design</span>
      <span class="experience-tag">PyTorch</span>
      <span class="experience-tag">Bash</span>
    </div>
  </div>

  <div class="experience-item">
    <h3>Summer Intern — NIELIT Calicut</h3>
    <p class="experience-date">May 2025 – June 2025</p>
    <p>
      Hands-on training in FPGA-based digital system design, RTL synthesis, and hardware prototyping, covering the complete RTL to bitstream workflow and multiple digital system implementations.
    </p>
    <div class="experience-skills">
      <span class="experience-tag">Verilog</span>
      <span class="experience-tag">FPGA</span>
      <span class="experience-tag">RTL Design &amp; Synthesis</span>
      <span class="experience-tag">Vivado</span>
    </div>
  </div>

  <div class="experience-item">
    <h3>Research Intern — TiHAN, IIT Hyderabad</h3>
    <p class="experience-date">June 2024 – July 2024</p>
    <p>
      Developed and trained a Machine Learning Model for an ADAS-based Project, achieving over 94% accuracy. Also worked as a Project Intern on Network Handover between Cellular Networks (4G LTE) and Wi-Fi Network, using Bash and OpenAir Interface in Unix CLI.
    </p>
    <div class="experience-skills">
      <span class="experience-tag">Machine Learning</span>
      <span class="experience-tag">TensorFlow 2.0</span>
      <span class="experience-tag">Network Handover</span>
      <span class="experience-tag">Bash</span>
      <span class="experience-tag">Linux</span>
    </div>
  </div>
</div>

  </section>

  <section>
    <div class="card">
      <h2>Beyond Engineering</h2>
      <p>Apart from STEM, I also:</p>
      <ul class="compact-list">
        <li>Carry the passion for music and singing, as a certified Carnatic vocalist and a former musical performer</li>
        <li>Am a public speaker, and an Emcee</li>
        <li>Enjoy trekking, hiking and adventure sports!</li>
      </ul>
    </div>
  </section>

</div>
