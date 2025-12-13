---
layout: home
title: Home
---
<style>
.hero-section {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 3rem;
  margin: 2rem 0 3rem 0;
  padding: 2rem;
  background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
  border-radius: 15px;
}

.hero-text {
  flex: 1;
}

.hero-text h1 {
  margin-top: 0;
  font-size: 2.5rem;
  color: #2c3e50;
}

.hero-text h2 {
  font-size: 1.2rem;
  color: #0066cc;
  font-weight: normal;
  margin: 1rem 0;
}

.hero-image {
  flex-shrink: 0;
  position: relative;
}

.hero-image img {
  width: 220px;
  height: 220px;
  border-radius: 50%;
  object-fit: cover;
  border: 5px solid white;
  box-shadow: 0 10px 30px rgba(0, 0, 0, 0.3);
  transition: transform 0.3s ease;
}

.hero-image img:hover {
  transform: scale(1.05) rotate(5deg);
}

.hero-image::before {
  content: '';
  position: absolute;
  top: -10px;
  right: -10px;
  width: 240px;
  height: 240px;
  border-radius: 50%;
  border: 3px dashed #0066cc;
  animation: rotate 20s linear infinite;
}

@keyframes rotate {
  from { transform: rotate(0deg); }
  to { transform: rotate(360deg); }
}

@media (max-width: 768px) {
  .hero-section {
    flex-direction: column;
    text-align: center;
  }
  
  .hero-text h1 {
    font-size: 1.8rem;
  }
  
  .hero-image img {
    width: 180px;
    height: 180px;
  }
}
</style>

<div class="hero-section">
  <div class="hero-text">
    <h1>Hi, welcome to my portfolio!</h1>
    <h2>Electronics & Communication Engineering | VLSI Design | AI-ML Enthusiast | Embedded Systems</h2>
    <p>I'm a B.Tech student at <strong>IIITDM Kurnool</strong>, passionate about designing intelligent hardware systems, while working at the intersection of <strong>VLSI</strong> and <strong>Machine Learning</strong> as well as <strong>Embedded Systems</strong>.</p>
  </div>
  
  <div class="hero-image">
    <img src="/assets/images/profile.jpg" alt="Kirthana P Rao">
  </div>
</div>

<p>As a tech enthusiast, I explore current innovations in the industry and research their engineering methodology(s). I love to practically apply my knowledge in building efficient real-world solutions.</p>

---

## What I Do

I specialize in:

**Hardware Design** - Creating optimized digital systems from RTL to silicon, with expertise in FPGA prototyping and RISC-V architecture

**AI-ML Integration** - Developing machine learning models for autonomous systems and exploring hardware acceleration techniques

**Embedded Systems** - Building IoT solutions and embedded applications that bridge software intelligence with hardware efficiency

---

## 🌟 Recent Highlights

🎓 **Samsung ISWDP Fellowship Recipient** - Selected as a trainee in semiconductor design and fabrication
🥈 **Silver Medal** - NPTEL Industry 4.0 & Industrial IoT Course  
🤖 **2nd Runner-up** - RoboRythm Competition, SOLASTA Techno-Cultural Fest 2K24  
⭐ **Top 0.1%** - Computer Science, CBSE Class XII Boards 2022

---

## 💼 Featured Work

### Compressor-Based Dadda Multiplier
Optimized 8×8 bit multiplier achieving **16% speed improvement** and **8% power reduction** using advanced compression techniques in Xilinx Vivado.

### RISC-V Pipelined Processor
Designed and implemented a multi-stage pipelined RISC-V processor with comprehensive hazard handling and instruction decoding in TL-Verilog.


[View All Projects →](/projects)

---

## 🛠️ Technical Toolkit

**Hardware:** Verilog, TL-Verilog, FPGA (Xilinx Vivado), RTL Design, RISC-V ISA  
**Software:** Python, C, C++, TensorFlow, MySQL
**Tools:** Cadence Virtuoso, OpenLANE, KiCAD, Git, Linux OS, VS Code

[Explore My Skills →](/skills)

---

## 📚 Continuous Learning

I'm certified in:
- Machine Learning Specialization (Stanford & DeepLearning.AI)
- Neural Networks & CNNs (DeepLearning.AI)
- VLSI Design Flow: RTL to GDS (NPTEL) & C-based VLSI Design(NPTEL)
- Minor Degree in Internet of Things (IoT)

---

## 🎵 Beyond the Code

When I'm not designing circuits or training models, I'm:
- 🎤 a stage-performer, as a trained Carnatic vocalist, and an orator cum emcee
- 🔧 Exploring and learning possible innovations in the world of Semiconductor and AI
- 🌍 Exploring food, culture, and lifestyle around the world

---

## Let's Connect

I'm always open to discussing new opportunities, collaborations, or innovative ideas in VLSI, AI-ML, and Embedded Systems.

**Email:** kirthanaprao@gmail.com  
**LinkedIn:** [My LinkedIn](https://www.linkedin.com/in/kirthana-p-6b89b326b/)  
**GitHub:** [Github](https://github.com/kirthana1181)  
**Phone:** +91 9497024531

[Get in Touch →](/contact)

---

## 🚀 Open to Opportunities

Currently seeking **internships** and **research positions** in:
- VLSI Design & Verification
- AI Hardware Acceleration
- FPGA Development
- Embedded Systems Engineering

---

*"Designing tomorrow's intelligent systems."*
