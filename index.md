---
layout: home
---

<div style="
  display:flex;
  justify-content:center;
  gap:2rem;
  margin:1rem 0;
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
  margin-bottom: 0.5rem;
}

h2 {
  font-size: 1.5rem;
  color: var(--secondary);
}

h3 {
  font-size: 1.2rem;
  margin-top: 1.5rem;
  margin-bottom: 0.5rem;
}

section {
  margin: 2.5rem auto;
}

a {
  color: var(--primary);
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

/* REGULAR CARDS - Narrower for readability */
.card {
  background: var(--card);
  padding: 2rem;
  border-radius: 14px;
  box-shadow: 0 10px 25px rgba(0,0,0,0.06);
  margin: 0 auto 1.5rem auto;
  max-width: 850px;
}

/* HERO CARD - MUCH WIDER to stand out */
.hero-card {
  background: var(--card);
  padding: 3.5rem;
  border-radius: 14px;
  box-shadow: 0 10px 25px rgba(0,0,0,0.06);
  margin: 0 auto 2rem auto;
  max-width: 1200px;
  border: 2px solid var(--primary);
}

.badge {
  display: inline-block;
  background: linear-gradient(135deg, var(--primary), var(--secondary));
  color: white;
  padding: 0.4rem 1rem;
  border-radius: 20px;
  font-size: 0.85rem;
  font-weight: 600;
  margin-bottom: 1rem;
}

/* HERO LAYOUT: Centered image on all screens */
.profile-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  text-align: center;
  gap: 2rem;
}

.profile-text {
  width: 100%;
}

.profile-image {
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0 auto;
}

.profile-image img {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid var(--primary);
  box-shadow: 0 8px 20px rgba(79, 70, 229, 0.3);
}

/* Desktop: Image and text side by side */
@media (min-width: 900px) {
  .profile-container {
    flex-direction: row;
    text-align: left;
    justify-content: space-between;
    align-items: center;
  }
  
  .profile-text {
    flex: 1;
    padding-right: 2rem;
  }
  
  .profile-image {
    flex-shrink: 0;
    margin: 0;
  }
}

/* Reusable list styling inside cards */
.card ul, .hero-card ul {
  margin: 1rem 0;
  padding-left: 1.5rem;
}

.card li, .hero-card li {
  margin-bottom: 0.5rem;
}

/* Social icons */
.socials {
  text-align: center;
  margin: 1rem 0;
}

.socials a {
  display: inline-block;
  margin: 0 0.5rem;
}

.socials img {
  filter: grayscale(1);
  transition: 0.3s;
}

.socials img:hover {
  filter: grayscale(0);
  transform: scale(1.1);
}

/* Mobile responsive */
@media (max-width: 768px) {
  .hero-card {
    padding: 2rem;
    max-width: 100%;
  }
  
  .card {
    padding: 1.5rem;
    max-width: 100%;
  }
  
  .profile-image img {
    width: 150px;
    height: 150px;
  }
  
  h1 {
    font-size: 2rem;
  }
  
  h2 {
    font-size: 1.2rem;
  }
}
</style>

---

<section>
  <div class="hero-card">
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
    <p>I'm certified in:</p>
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
    <h2>Let's Connect</h2>
    <p>
      I'm always open to discussing new opportunities, collaborations, or innovative ideas in VLSI, AI-ML, and Embedded Systems.
    </p>
    <p class="socials">
      <a href="https://www.linkedin.com/in/kirthana-p-6b89b326b/">
        <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/linkedin.svg" width="34" height="34" alt="LinkedIn" />
      </a>
      <a href="https://github.com/kirthana1181">
        <img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/github.svg" width="34" height="34" alt="GitHub" />
      </a>
      <a href="mailto:work.kirthana@gmail.com">
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
    <p><em>"Designing tomorrow's intelligent systems."</em></p>
  </div>
</section>
