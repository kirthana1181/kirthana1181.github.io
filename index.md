---
layout: home
---

<div style="
  display:flex;
  justify-content:center;
  gap:2rem;
  margin:2rem 0;
  font-weight:600;">
  <a href="/projects">Projects</a>
  <a href="/skills">Skills</a>
</div>

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
}

body {
  font-family: "Inter", "Segoe UI", sans-serif;
  background: var(--bg);
  color: var(--text);
  line-height: 1.7;
}

h1, h2, h3 {
  font-weight: 700;
  letter-spacing: -0.02em;
}

h1 {
  font-size: 2.6rem;
}

h2 {
  font-size: 1.5rem;
  color: var(--secondary);
}

section {
  margin: 4rem 0;
}

a {
  color: var(--primary);
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

.card {
  background: var(--card);
  padding: 1.8rem;
  border-radius: 14px;
  box-shadow: 0 10px 25px rgba(0,0,0,0.06);
  margin-bottom: 1.5rem;
}

/* HERO LAYOUT: text + photo side by side */
.profile-container {
  display: flex;
  flex-wrap: wrap;
  gap: 2rem;
  align-items: center;
  justify-content: space-between;
}

.profile-text {
  flex: 1 1 280px;
}

.profile-image {
  flex: 0 0 auto;
}

.profile-image img {
  max-width: 260px;
  border-radius: 14px;
  display: block;
}

/* Reusable list styling inside cards */
.card ul {
  margin: 0;
  padding-left: 1.2rem;
}

.card li {
  margin-bottom: 0.3rem;
}

/* Social icons */
.socials img {
  filter: grayscale(1);
  transition: 0.3s;
}

.socials img:hover {
  filter: grayscale(0);
  transform: scale(1.1);
}
</style>

---

<section class="card">
  <div class="profile-container">
    <div class="profile-text">
      <span class="badge">ECE • VLSI • AI-ML • Embedded Systems</span>
      <h1>Hi, I'm Kirthana</h1>
      <h2>Electronics &amp; Communication Engineering | VLSI Design | AI-ML Enthusiast | Embedded Systems</h2>
      <p>
        I'm a B.Tech student at <strong>IIITDM Kurnool</strong>, passionate about designing intelligent hardware systems, while working at the intersection of
        <strong>VLSI</strong> and <strong>Machine Learning</strong> as well as <strong>Embedded Systems</strong>. I love to practically apply my knowledge in building efficient real-world solutions.
      </p>
    </div>

    <div class="profile-image">
      <img src="/assets/images/profile.jpg" alt="Profile photo of Kirthana">
    </div>
  </div>
</section>

<section>
  <div class="card">
    <h2>What I Do</h2>
    <p><strong>Hardware Design</strong> – Creating optimized digital systems from RTL to silicon, with expertise in FPGA prototyping and RISC-V architecture.</p>
    <p><strong>AI-ML Integration</strong> – Developing machine learning models for autonomous systems and exploring hardware acceleration techniques.</p>
    <p><strong>Embedded Systems</strong> – Building IoT solutions and embedded applications that bridge software intelligence with hardware efficiency.</p>
  </div>
</section>

<section>
  <div class="card">
    <h2>Highlights &amp; Achievements</h2>
    <ul>
      <li><strong>Samsung ISWDP Fellowship Recipient</strong> – Selected as a trainee in semiconductor design and fabrication.</li>
      <li><strong>Silver Medal</strong> – NPTEL Industry 4.0 &amp; Industrial IoT Course.</li>
      <li><strong>2nd Runner-up</strong> – RoboRythm Competition, SOLASTA Techno-Cultural Fest 2K24.</li>
      <li><strong>Top 0.1%</strong> – Computer Science, CBSE Class XII Boards 2022.</li>
    </ul>
  </div>
</section>

<section>
  <div class="card">
    <h2>Featured Work</h2>
    <h3>Compressor-Based Dadda Multiplier</h3>
    <p>
      Optimized 8×8 bit multiplier achieving <strong>16% speed improvement</strong> and <strong>8% power reduction</strong>
      using advanced compression techniques in Xilinx Vivado.
    </p>
    <h3>RISC-V Pipelined Processor</h3>
    <p>
      Designed and implemented a multi-stage pipelined RISC-V processor with comprehensive hazard handling and instruction decoding in TL-Verilog.
    </p>
    <p><a href="/projects">View All Projects →</a></p>
  </div>
</section>

<section>
  <div class="card">
    <h2>Technical Toolkit</h2>
    <p><strong>Hardware:</strong> Verilog, TL-Verilog, FPGA (Xilinx Vivado), RTL Design, RISC-V ISA.</p>
    <p><strong>Software:</strong> Python, C, C++, TensorFlow, MySQL.</p>
    <p><strong>Tools:</strong> Cadence Virtuoso, OpenLANE, KiCAD, Git, Linux OS, VS Code.</p>
    <p><a href="/skills">Explore My Skills →</a></p>
  </div>
</section>

<section>
  <div class="card">
    <h2>Continuous Learning 💡</h2>
    <p>I’m certified in:</p>
    <ul>
      <li>Machine Learning Specialization (Stanford &amp; DeepLearning.AI).</li>
      <li>Neural Networks &amp; CNNs (DeepLearning.AI).</li>
      <li>VLSI Design Flow: RTL to GDS (NPTEL) &amp; C-based VLSI Design (NPTEL).</li>
      <li>Minor Degree in Internet of Things (IoT).</li>
    </ul>
  </div>
</section>

<section>
  <div class="card">
    <h2>Beyond the Code 🎵</h2>
    <ul>
      <li>A stage performer, trained Carnatic vocalist, and an orator cum emcee 🎤.</li>
      <li>Exploring and learning possible innovations in the world of Semiconductor and AI 🔧.</li>
      <li>Exploring food, culture, and lifestyle around the world 🌍.</li>
    </ul>
  </div>
</section>

<section>
  <div class="card">
    <h2>Let’s Connect</h2>
    <p>
      I’m always open to discussing new opportunities, collaborations, or innovative ideas in VLSI, AI-ML, and Embedded Systems.
    </p>
    <p align="center" class="socials">
      <a href="https://www.linkedin.com/in/kirthana-p-6b89b326b/">
        <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/linkedin.svg" width="34" height="34" alt="LinkedIn" />
      </a>
      <a href="https://github.com/kirthana1181">
        <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/github.svg" width="34" height="34" alt="GitHub" />
      </a>
      <a href="mailto:work.kirthana@email.com">
        <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/gmail.svg" width="34" height="34" alt="Email" />
      </a>
    </p>
  </div>
</section>

<section>
  <div class="card">
    <h2>Open to Opportunities</h2>
    <p>Currently seeking <strong>internships</strong> and <strong>research positions</strong> in:</p>
    <ul>
      <li>VLSI Design &amp; Verification.</li>
      <li>AI Hardware Acceleration.</li>
      <li>FPGA Development.</li>
      <li>Embedded Systems Engineering.</li>
    </ul>
    <p><em>“Designing tomorrow’s intelligent systems.”</em></p>
  </div>
</section>
