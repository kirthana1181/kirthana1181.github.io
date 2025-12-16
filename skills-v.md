---
layout: page
title: Skills & Tools
---
<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
        line-height: 1.6;
        color: #333;
        background: #fff;
    }

    /* Navigation */
    nav {
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        padding: 1rem 2rem;
        box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    nav a {
        color: white;
        text-decoration: none;
        font-weight: 500;
        padding: 0.5rem 1rem;
        border-radius: 20px;
        transition: background 0.3s ease;
    }

    nav a:hover {
        background: rgba(255,255,255,0.2);
    }

    .container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 2rem;
    }

    h1 {
        text-align: center;
        color: #333;
        margin: 2rem 0;
        font-size: 2.5rem;
    }

    h2 {
        color: #0066cc;
        margin: 2rem 0 1rem;
        font-size: 1.8rem;
        border-bottom: 3px solid #0066cc;
        padding-bottom: 0.5rem;
    }

    /* Skills Grid */
    .skills-grid {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
        gap: 2rem;
        margin: 2rem 0;
    }

    .skill-category {
        background: #f8f9fa;
        padding: 1.5rem;
        border-radius: 8px;
        border-left: 4px solid #0066cc;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .skill-category:hover {
        transform: translateY(-5px);
        box-shadow: 0 5px 15px rgba(0,0,0,0.1);
    }

    .skill-category h3 {
        margin-top: 0;
        color: #333;
        font-size: 1.3rem;
        margin-bottom: 1rem;
    }

    .skill-tags {
        display: flex;
        flex-wrap: wrap;
        gap: 0.5rem;
        margin-top: 1rem;
    }

    .skill-tag {
        background: #fff;
        padding: 0.4rem 0.8rem;
        border-radius: 20px;
        font-size: 0.9rem;
        border: 1px solid #ddd;
        display: inline-flex;
        align-items: center;
        gap: 0.3rem;
        transition: all 0.2s ease;
    }

    .skill-tag:hover {
        background: #0066cc;
        color: white;
        border-color: #0066cc;
        transform: scale(1.05);
    }

    /* Certifications */
    .cert-list {
        list-style: none;
        padding: 0;
    }

    .cert-list li {
        background: #f8f9fa;
        padding: 1rem;
        margin: 0.5rem 0;
        border-radius: 5px;
        border-left: 4px solid #667eea;
    }

    .cert-badge {
        display: inline-block;
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        color: white;
        padding: 0.3rem 0.8rem;
        border-radius: 5px;
        margin-right: 0.5rem;
        font-size: 0.85rem;
        font-weight: 600;
    }

    .cert-badge.silver {
        background: linear-gradient(135deg, #bdc3c7 0%, #2c3e50 100%);
    }

    /* Proficiency Bars */
    .proficiency-section {
        margin: 2rem 0;
    }

    .proficiency-item {
        margin: 1.5rem 0;
    }

    .proficiency-label {
        display: flex;
        justify-content: space-between;
        margin-bottom: 0.5rem;
        font-weight: 500;
    }

    .proficiency-bar {
        background: #e0e0e0;
        height: 10px;
        border-radius: 5px;
        overflow: hidden;
    }

    .proficiency-fill {
        height: 100%;
        background: linear-gradient(90deg, #0066cc, #00cc66);
        transition: width 1s ease;
    }

    /* Footer */
    footer {
        text-align: center;
        padding: 2rem;
        background: #f8f9fa;
        border-radius: 10px;
        margin-top: 3rem;
    }

    footer p {
        color: #666;
        margin-bottom: 1rem;
    }

    .back-home-btn {
        display: inline-block;
        padding: 0.8rem 2rem;
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        color: white;
        text-decoration: none;
        border-radius: 25px;
        font-weight: 500;
        transition: all 0.3s ease;
    }

    .back-home-btn:hover {
        transform: translateY(-2px);
        box-shadow: 0 5px 15px rgba(102, 126, 234, 0.4);
    }

    @media (max-width: 768px) {
        .skills-grid {
            grid-template-columns: 1fr;
        }
        h1 {
            font-size: 2rem;
        }
        .container {
            padding: 1rem;
        }
    }
</style>
---
<div style="text-align: center; margin: 2rem 0; padding: 1rem; background: #f8f9fa; border-radius: 10px;">
<a href="/index.md" style="margin: 0 1rem; color: #667eea; font-weight: 500;">Home</a> |
<a href="/projects.html" style="margin: 0 1rem; color: #667eea; font-weight: 500;">Projects</a> 
</div>

## 💻 Things I Do

### 🔧 Hardware Description Languages
**Verilog** · **SystemVerilog** · **TL-Verilog**

### ✅ Verification
**Universal Verification Methodology (UVM)**

### 🐍 Programming Languages
**Python** · **C** · **C++**

### 🌐 Web Development
**HTML5** · **CSS3**

### 📜 Scripting
**Bash** · **Tcl** · **Python Scripts**

---

## 🧰 Tools & Libraries

### 💼 Development Environment
**Visual Studio Code** · **Git** <img src="https://cdn.simpleicons.org/github/181717" alt="GitHub" width="16" height="16" style="vertical-align: middle;"> · **Jupyter Notebook** · **Spyder**

### ⚡ FPGA & Digital Design
**Xilinx Vivado** · **Xilinx ISE** · **GTKWave** · **ModelSim** · **Questa**

### 🎨 Analog & Circuit Design
**Cadence Virtuoso** · **LTSpice** · **Multisim** · **Tina-Ti**

### 📐 PCB Design & Layout
**KiCAD** · **Eagle** · **Altium Designer**

### 🏗️ ASIC Design Flow
**OpenLANE** · **OpenSTA** · **Magic** · **Yosys**

### 🔬 Physical Design
**Cadence Innovus** · **Cadence Genus** · **Synopsys Design Compiler**

### 🧮 Simulation & Analysis
**MATLAB** · **Simulink** · **Octave**

### 📊 HDL Simulation
**Icarus Verilog** · **Verilator** · **GHDL**

---

## 💾 Operating Systems

**Windows** 🪟 · **Linux** 🐧 (Ubuntu, Debian, Fedora)

---

## 🔌 Development Boards & Hardware

### Microcontrollers
**Arduino** (Uno, Mega, Nano) · **ESP32** · **ESP8266** · **LPC-2148** · **STM32**

### FPGA Boards
**Xilinx Artix-7** · **Spartan-6** · **Zynq-7000**

### Development Kits
**Aries Vega Processors** · **TI LaunchPad** · **Raspberry Pi**

---

## 🏛️ Architectures & Protocols

### Processor Architectures
**RISC-V ISA** · **ARM Cortex** · **AVR** · **PIC**

### Communication Protocols
**AXI4** · **AXI4-Lite** · **APB** · **AHB** · **I2C** · **SPI** · **UART** · **USB**

### Memory Interfaces
**DDR3/DDR4** · **SDRAM** · **Flash**

---

## 🤖 AI/ML & Data Science

### Frameworks
**TensorFlow 2.0** · **Keras** · **PyTorch** · **Scikit-learn**

### Libraries
**NumPy** · **Pandas** · **Matplotlib** · **OpenCV**

### Specializations
- Neural Networks & Deep Learning
- Convolutional Neural Networks (CNNs)
- Computer Vision
- Autonomous Systems

---

## 🛠️ Software Development Practices

### Version Control
**Git** · **GitHub** · **GitLab** · **Bitbucket**

### Methodologies
**Agile** · **Scrum** · **Test-Driven Development (TDD)**

### Programming Paradigms
**Object-Oriented Programming (OOP)** · **Functional Programming** · **Hardware-Software Co-design**

---

## 📚 Certifications

### 🎓 Machine Learning & AI
- ✅ **Machine Learning Specialization** - Stanford University & DeepLearning.AI (Coursera)
- ✅ **Neural Networks and CNNs** - DeepLearning.AI (Coursera)
- ✅ **Deep Learning Specialization** - DeepLearning.AI

### 🔌 VLSI & Hardware Design
- ✅ **VLSI Design Flow: RTL to GDS** - NPTEL (IIIT Delhi)
- ✅ **Digital Design with Verilog** - NPTEL (IIT Guwahati)
- ✅ **C-Based VLSI Design** - NPTEL (IIT Guwahati)
- ✅ **Physical Design of ASICs** - NPTEL

### 🌐 IoT & Industry 4.0
- ✅ **Minor Degree in Internet of Things (IoT)** - IIITDM Kurnool
- 🥈 **Introduction to Industry 4.0 and Industrial IoT** - NPTEL (IIT Kharagpur) - **Silver Medal**

### 🏆 Special Recognition
- ⭐ **ISWDP Samsung Student Fellowship Recipient**
- 🏅 **DVCon India Design Contest 2025** - Stage 1 Shortlisted

---

## 🎯 Core Competencies

### Hardware Design
- RTL Design & Synthesis
- FPGA Prototyping & Implementation
- ASIC Design Flow (RTL to GDSII)
- Timing Analysis & Optimization
- Power Analysis & Low-Power Design
- Design for Testability (DFT)

### Verification
- Testbench Development
- Functional Verification
- UVM Methodology
- Assertion-Based Verification
- Coverage-Driven Verification

### Embedded Systems
- Real-Time Operating Systems (RTOS)
- IoT System Design
- Sensor Integration

### AI/ML
- Model Development & Training
- Neural Network Architecture Design
- Computer Vision Applications
- Hardware Acceleration for ML
- Edge AI Implementation

---

## 🌱 Currently Learning

- 🔥 Advanced UVM Verification Techniques
- 🚀 SystemVerilog Assertions (SVA)
- 🧠 Hardware Acceleration for Deep Learning
- ⚡ High-Performance Computing Architectures
- 🔐 Hardware Security & Trust

---

## 📊 Skill Proficiency

### Expert Level ⭐⭐⭐⭐⭐
Verilog · C · Python · RTL Design · FPGA Development

### Advanced Level ⭐⭐⭐⭐
SystemVerilog · C++ · TensorFlow · Digital Design · Embedded Systems

### Intermediate Level ⭐⭐⭐
UVM · ASIC Design · PCB Design · MATLAB · Web Development

### Learning 📚
Formal Verification · Chip Design · Advanced DFT · Quantum Computing

---

*Skills continuously evolving. Last updated: December 2025*

---

<div style="text-align: center; padding: 2rem 0; background: #f8f9fa; border-radius: 10px; margin-top: 2rem;">
  <p style="color: #666; margin-bottom: 1rem;">&copy; 2025 Kirthana P Rao. All rights reserved.</p>
  <a href="/" style="display: inline-block; padding: 0.8rem 2rem; background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); color: white; text-decoration: none; border-radius: 25px; font-weight: 500; transition: all 0.3s ease;">
    🏠 Back to Home
  </a>
</div>
