---
layout: splash
classes: wide
---

<style>
:root {
  --primary: #4f46e5;
  --secondary: #6366f1;
  --accent: #22c55e;
  --bg: #f9fafb;
  --text: #111827;
  --muted: #6b7280;
  --card: #ffffff;
  --border: #e5e7eb;
}

body {
  font-family: "Inter", "Segoe UI", sans-serif;
  background: var(--bg);
  color: var(--text);
  line-height: 1.55;
}

.portfolio-shell {
  width: min(1050px, calc(100% - 2rem));
  margin: 0 auto;
}


section {
  margin: 1rem 0;
}

h1,
h2,
h3 {
  font-weight: 700;
  letter-spacing: -0.02em;
}

h1 {
  font-size: 2.25rem;
  margin: 0 0 0.25rem;
}

h2 {
  color: var(--secondary);
  font-size: 1.3rem;
  margin: 0 0 0.75rem;
}

h3 {
  font-size: 1.05rem;
  margin: 0 0 0.25rem;
}

p {
  margin: 0.45rem 0;
}

.card,
.hero-card,
.cta-card {
  background: var(--card);
  border-radius: 14px;
  box-shadow: 0 8px 22px rgba(0, 0, 0, 0.055);
}

.card {
  padding: 1.25rem 1.5rem;
}

.hero-card {
  padding: 2rem 2.25rem;
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
  width: 140px;
  height: 140px;
  border: none;
  border-radius: 50%;
  object-fit: cover;
  box-shadow: none;
}

.profile-text {
  min-width: 0;
}

.hero-role {
  color: var(--secondary);
  font-size: 1.08rem;
  font-weight: 650;
  margin: 0 0 0.55rem;
}

.focus-chips,
.opportunity-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.45rem;
  margin-top: 0.8rem;
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
  gap: 0.65rem;
  margin-top: 1rem;
}

.button {
  display: inline-block;
  padding: 0.55rem 0.95rem;
  border-radius: 8px;
  background: var(--primary);
  color: #fff !important;
  font-size: 0.9rem;
  font-weight: 650;
  text-decoration: none !important;
}

.button.secondary {
  background: #eef2ff;
  color: #3730a3 !important;
  border: 1px solid #c7d2fe;
}

.proof-bar {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 0.75rem;
}

.proof-item {
  padding: 0.9rem;
  border: 1px solid var(--border);
  border-radius: 10px;
  background: var(--card);
  text-align: center;
}

.proof-item strong {
  display: block;
  color: var(--primary);
  font-size: 0.95rem;
}

.proof-item span {
  display: block;
  color: var(--muted);
  font-size: 0.78rem;
  line-height: 1.35;
  margin-top: 0.2rem;
}

.two-column {
  display: grid;
  grid-template-columns: 1.3fr 1fr;
  gap: 1rem;
}

.equal-columns {
  grid-template-columns: 1fr 1fr;
}

.project-preview + .project-preview {
  margin-top: 0.9rem;
  padding-top: 0.9rem;
  border-top: 1px solid var(--border);
}

.compact-list {
  margin: 0.45rem 0 0;
  padding-left: 1.2rem;
}

.compact-list li {
  margin-bottom: 0.3rem;
}

.tool-row {
  margin-bottom: 0.7rem;
}

.tool-row:last-of-type {
  margin-bottom: 0;
}

.cta-card {
  padding: 1.25rem 1.5rem;
  border-left: 4px solid var(--accent);
}

.cta-content {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 1rem;
}

.socials {
  display: flex;
  flex: 0 0 auto;
  gap: 0.65rem;
}

.socials img {
  display: block;
  width: 28px;
  height: 28px;
  filter: grayscale(1);
  transition: 0.2s ease;
}

.socials img:hover {
  filter: grayscale(0);
  transform: translateY(-2px);
}

.masthead__menu-item a { color: #4f46e5 !important; }


.experience-item + .experience-item {
  margin-top: 0.85rem;
  padding-top: 0.85rem;
  border-top: 1px solid var(--border);
}

.experience-item h3 {
  margin: 0 0 0.2rem;
  font-size: 1rem;
}

.experience-item p {
  margin: 0.25rem 0;
  font-size: 0.9rem;
}

.experience-date {
  color: var(--muted);
  font-size: 0.8rem !important;
  font-weight: 600;
}

.experience-skills {
  display: flex;
  flex-wrap: wrap;
  gap: 0.35rem;
  margin-top: 0.55rem;
}

.experience-tag {
  display: inline-block;
  padding: 0.25rem 0.6rem;
  border: 1px solid #c7d2fe;
  border-radius: 999px;
  background: #eef2ff;
  color: #3730a3;
  font-size: 0.75rem;
  font-weight: 600;
}
  
@media (max-width: 768px) {
  .portfolio-shell {
    width: min(100% - 1rem, 1050px);
  }
  .profile-image img {
    width: 115px;
    height: 115px;
  }
}
 
</style>

<div class="portfolio-shell">
  <section>
    <div class="hero-card">
      <div class="profile-container">
        <div class="profile-image">
          <img src="/assets/images/profile.jpg" alt="Profile photo of Kirthana">
        </div>

        <div class="profile-text">
          <h1>Hi, I'm Kirthana</h1>
          <p class="hero-role">Project Associate at IISc, Bangalore</p>
          <p>
             Project Associate at IISc, Bangalore, at the Future Computing Systems (FIST) Research Group, at the Dept. of CSA, with deep interest in the areas of VLSI, AI and Embedded System Design.
          </p>

          <!-- <div class="focus-chips" aria-label="Focus areas">
            <span class="focus-chip">RTL &amp; Design</span>
            <span class="focus-chip">AI Hardware</span>
            <span class="focus-chip">Embedded Systems &amp; VLSI</span>
          </div> -->

          <div class="hero-actions">
            <a class="button" href="/projects">View Projects</a>
            <a class="button secondary" href="/assets/docs/KIRTHANA P RAO_CV1.pdf" download>
              Download CV
            </a>
            <a class="button secondary" href="/contact.html">Contact Me</a>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section aria-label="Highlights and achievements">
    <div class="proof-bar">
      <div class="proof-item">
        <strong>Samsung ISWDP</strong>
        <span>Semiconductor Fellowship Recipient</span>
      </div>
      <!-- <div class="proof-item">
        <strong>NPTEL Silver</strong>
        <span>Industry 4.0 and Industrial IoT</span>
      </div> -->
      <div class="proof-item">
        <strong>RoboRythm</strong>
        <span>Second Runner-Up at SOLASTA 2K24</span>
      </div>
      <!-- <div class="proof-item">
        <strong>CBSE Top 0.1%</strong>
        <span>Computer Science, </span>
      </div> -->
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
      <p class="tool-row"><strong>Hardware:</strong> Verilog HDL, TL-Verilog HDL, FPGA, RTL, RISC-V.</p>
      <p class="tool-row"><strong>Software:</strong> Python, C, C++, TensorFlow.</p>
      <p class="tool-row"><strong>Tools:</strong> Vivado, Virtuoso, OpenLANE, KiCad, Git, Linux.</p>
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
      Worked on developing an end-to-end implementation framework for depoying ML Algorithms on FPGAs, as part of an industry project at the Future Computing Systems (FIST) Research group, at the Dept. of Computer Science & Automation.
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
      <span class="experience-tag">RTL Design & Synthesis</span>
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
      <span class="experience-tag">Tensorflow 2.0</span>
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
      <p> Apart from STEM, I also: </p>
      <ul class="compact-list">
        <li> Carry the passion for music and singing, as a certified carnatic vocalist and a former musical perfomer</li>
        <li> Am a public speaker, and an Emcee</li>
        <li> Enjoy trekking, hiking and adventure sports!</li>
      </ul>
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
