---
layout: home
---

<style>
:root{
  --primary:#4f46e5;
  --primary-2:#6366f1;
  --accent:#22c55e;
  --bg:#f8fafc;
  --card:#ffffff;
  --text:#111827;
  --muted:#6b7280;
  --border:#e5e7eb;
}

body{
  font-family:"Inter","Segoe UI",sans-serif;
  background:var(--bg);
  color:var(--text);
  line-height:1.65;
}

section{
  margin:1.5rem auto;
  max-width:980px;
}

a{
  color:var(--primary);
  text-decoration:none;
}
a:hover{
  text-decoration:underline;
}

.hero-card,.card{
  background:var(--card);
  border:1px solid var(--border);
  border-radius:16px;
  box-shadow:0 10px 28px rgba(15,23,42,.06);
}

.hero-card{
  padding:1.8rem;
  margin:0 auto 1rem auto;
}

.card{
  padding:1.35rem 1.5rem;
  margin:0 auto 1rem auto;
}

.badge{
  display:inline-flex;
  align-items:center;
  gap:.4rem;
  background:linear-gradient(135deg,var(--primary),var(--primary-2));
  color:white;
  padding:.35rem .85rem;
  border-radius:999px;
  font-size:.84rem;
  font-weight:700;
  margin-bottom:.85rem;
}

.profile-container{
  display:grid;
  grid-template-columns:160px 1fr;
  gap:1.5rem;
  align-items:center;
}

.profile-image img{
  width:160px;
  height:160px;
  border-radius:50%;
  object-fit:cover;
  border:4px solid var(--primary);
  box-shadow:0 10px 24px rgba(79,70,229,.22);
}

.profile-text{
  width:100%;
}

h1,h2,h3{
  font-weight:800;
  letter-spacing:-0.02em;
  margin:0;
}

h1{
  font-size:2.2rem;
  margin-bottom:.35rem;
}

h2{
  font-size:1.3rem;
  color:var(--primary);
  margin-bottom:.75rem;
}

h3{
  font-size:1.05rem;
  margin:1rem 0 .4rem;
}

.card p,.hero-card p{
  margin:.4rem 0;
  color:#374151;
}

.quick-grid{
  display:grid;
  grid-template-columns:repeat(3,minmax(0,1fr));
  gap:1rem;
}

.mini-card{
  background:#f9fafb;
  border:1px solid var(--border);
  border-radius:14px;
  padding:1rem;
}

.mini-card h3{
  margin-top:0;
}

ul{
  margin:.5rem 0 .2rem 1.2rem;
  padding:0;
}

li{
  margin-bottom:.35rem;
}

.socials{
  display:flex;
  gap:.65rem;
  align-items:center;
  flex-wrap:wrap;
  margin-top:.75rem;
}

.socials a{
  display:inline-flex;
  align-items:center;
  justify-content:center;
  width:38px;
  height:38px;
  border-radius:50%;
  background:#f3f4f6;
  border:1px solid var(--border);
  transition:transform .2s ease, box-shadow .2s ease;
}

.socials a:hover{
  transform:translateY(-2px);
  box-shadow:0 6px 14px rgba(15,23,42,.08);
  text-decoration:none;
}

.socials img{
  width:20px;
  height:20px;
}

.tool-list{
  display:flex;
  flex-wrap:wrap;
  gap:.5rem;
  margin-top:.75rem;
}

.tool-pill{
  display:inline-flex;
  align-items:center;
  gap:.4rem;
  padding:.42rem .75rem;
  border-radius:999px;
  border:1px solid var(--border);
  background:#fff;
  font-size:.9rem;
  color:#374151;
}

.tool-pill strong{
  font-weight:600;
}

@media (max-width: 768px){
  section{
    margin:1rem auto;
  }
  .hero-card,.card{
    padding:1.1rem;
  }
  .profile-container{
    grid-template-columns:1fr;
    text-align:center;
    justify-items:center;
  }
  .profile-image img{
    width:132px;
    height:132px;
  }
  h1{
    font-size:1.8rem;
  }
  h2{
    font-size:1.1rem;
  }
  .quick-grid{
    grid-template-columns:1fr;
  }
}
</style>

<section>
  <div class="hero-card">
    <div class="profile-container">
      <div class="profile-image">
        <img src="/assets/images/profile.jpg" alt="Profile photo of Kirthana">
      </div>
      <div class="profile-text">
        <span class="badge">ECE • VLSI • AI/ML • Embedded Systems</span>
        <h1>Hi, I’m Kirthana</h1>
        <h2>Electronics &amp; Communication Engineering | VLSI Design | AI-ML Enthusiast | Embedded Systems</h2>
        <p>
          I’m a B.Tech student at <strong>IIITDM Kurnool</strong>, focused on building practical hardware-software solutions across
          <strong>VLSI</strong>, <strong>embedded systems</strong>, and <strong>machine learning</strong>.
        </p>
        <div class="tool-list">
          <span class="tool-pill">RTL Design</span>
          <span class="tool-pill">FPGA Prototyping</span>
          <span class="tool-pill">AI Hardware</span>
        </div>
      </div>
    </div>
  </div>
</section>

<section class="quick-grid">
  <div class="mini-card">
    <h3>What I Do</h3>
    <p><strong>Hardware Design</strong> — RTL to silicon thinking, FPGA prototyping, and RISC-V based systems.</p>
    <p><strong>AI-ML Integration</strong> — Models, workflows, and accelerator-aware design exploration.</p>
    <p><strong>Embedded Systems</strong> — Sensor-driven and IoT-oriented applications.</p>
  </div>

  <div class="mini-card">
    <h3>Highlights</h3>
    <ul>
      <li>Samsung ISWDP Fellowship Recipient</li>
      <li>NPTEL Industry 4.0 &amp; IIoT Silver Medal</li>
      <li>2nd Runner-up — RoboRythm 2K24</li>
      <li>Top 0.1% in CBSE CS Boards</li>
    </ul>
  </div>

  <div class="mini-card">
    <h3>Featured Work</h3>
    <p><strong>Dadda Multiplier</strong> — 16% speed improvement and 8% power reduction.</p>
    <p><strong>RISC-V Processor</strong> — Multi-stage pipelined design with hazard handling.</p>
    <p><a href="/projects">View all projects →</a></p>
  </div>
</section>

<section class="card">
  <h2>Technical Toolkit</h2>
  <p><strong>Hardware:</strong> Verilog, TL-Verilog, FPGA, RTL Design, RISC-V ISA.</p>
  <p><strong>Software:</strong> Python, C, C++, TensorFlow, MySQL.</p>
  <p><strong>Tools:</strong> Cadence Virtuoso, OpenLANE, KiCAD, Git, Linux, VS Code.</p>
  <p><a href="/skills">Explore my skills →</a></p>
</section>

<section class="card">
  <h2>Continuous Learning</h2>
  <p>I’m currently building depth in RTL verification, DFT, UVM, and SystemVerilog while strengthening my hardware design and ML workflow skills.</p>
  <ul>
    <li>Machine Learning Specialization (Stanford &amp; DeepLearning.AI)</li>
    <li>Neural Networks &amp; CNNs (DeepLearning.AI)</li>
    <li>VLSI Design Flow: RTL to GDS (NPTEL)</li>
    <li>C-based VLSI Design (NPTEL)</li>
  </ul>
</section>

<section class="card">
  <h2>Let’s Connect</h2>
  <p>I’m open to internships, research, and collaborative work in VLSI, AI-ML, and Embedded Systems.</p>
  <div class="socials">
    <a href="https://www.linkedin.com/in/kirthana-p-6b89b326b/"><img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/linkedin.svg" alt="LinkedIn"></a>
    <a href="https://github.com/kirthana1181"><img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/github.svg" alt="GitHub"></a>
    <a href="mailto:work.kirthana@gmail.com"><img src="https://cdn.jsdelivr.net/npm/simple-icons@v9/icons/gmail.svg" alt="Email"></a>
  </div>
</section>

<section class="card">
  <h2>Beyond the Code</h2>
  <p>A trained Carnatic vocalist, stage performer, and emcee; also exploring semiconductor innovation, AI, food, and culture.</p>
</section>

<section class="card">
  <h2>Open to Opportunities</h2>
  <p>Currently seeking internships and research positions in:</p>
  <ul>
    <li>VLSI Design &amp; Verification</li>
    <li>AI Hardware Acceleration</li>
    <li>FPGA Development</li>
    <li>Embedded Systems Engineering</li>
  </ul>
</section>
