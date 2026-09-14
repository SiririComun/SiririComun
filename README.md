<div align="center">

# Hi, I'm Juan Pablo 👋

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=00FFCC&center=true&vCenter=true&width=620&lines=Hardware-Software+Co-Design+%E2%80%A2+FPGA+Systems;High-Performance+Computing+(C%2B%2B17+%2F+CUDA);Scientific+Instrumentation+%E2%80%A2+Wave+Physics;Developer+Tooling+%26+Automation+Architect" alt="Typing SVG" /></a>

<br>

[![Target](https://img.shields.io/badge/FPGA-Zynq--7000%20(PYNQ--Z2)-10B981?style=for-the-badge&logo=xilinx&logoColor=white)](https://github.com/SiririComun/hw-xadc-dma-overlays)
[![Compute](https://img.shields.io/badge/Compute-CUDA%20%7C%20C%2B%2B17-2563EB?style=for-the-badge&logo=cplusplus&logoColor=white)](https://github.com/SiririComun/Ising-Dynamics)
[![Research](https://img.shields.io/badge/Research-UdeA%20GICM-7C3AED?style=for-the-badge&logo=academia&logoColor=white)](https://www.udea.edu.co)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/pablosanchezarroyave/)

</div>

---

## 🏛️ Engineering Philosophy & Systems Vision

I am a **Physicist** at the **Universidad de Antioquia (UdeA)** and a **Junior Researcher in Microelectronics & Scientific Instrumentation (GICM)**.

My approach is grounded in **systems thinking**: I view algorithms not as isolated mathematical abstractions, but as physical processes that interface with silicon logic, clock constraints, memory hierarchies (L1/L2 cache), and communication buses.

* 🔬 **Scientific Instrumentation as a Bridge:** I design instruments to connect mathematical equations with experimental reality. Platforms are built from day one to be **modular, extensible, and easily replicable**, prioritizing open-source toolchains and reproducible standards.
* ⚡ **End-to-End HW/SW Co-Design:** I translate theoretical concepts down into reconfigurable silicon (FPGA/RTL) and high-throughput software (PYNQ, C++17, CUDA), optimizing full-stack data paths for maximum bandwidth and deterministic execution.
* 🛠️ **Pragmatic Automation & Tooling:** I treat the engineering lifecycle as a system to be optimized—architecting custom zero-dependency CLI tools, automated CI/CD validation gates, and reproducible environments that multiply velocity without technical debt.

---

## 📊 GitHub Engineering Analytics

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=SiririComun&theme=dark&background=0D1117&border=1E293B&stroke=00FFCC&ring=00FFCC&fire=00FFCC&currStreakLabel=00FFCC&sideNums=FFFFFF&sideLabels=94A3B8" alt="GitHub Streak" width="49%" />
<img src="https://github-stats-extended.vercel.app/api?username=SiririComun&show_icons=true&theme=dark&bg_color=0D1117&border_color=1E293B&title_color=00FFCC&text_color=94A3B8&icon_color=00FFCC&hide=issues" alt="GitHub Stats" width="49%" />

<br>

<img src="https://github-stats-extended.vercel.app/api/top-langs/?username=SiririComun&layout=compact&theme=dark&bg_color=0D1117&border_color=1E293B&title_color=00FFCC&text_color=94A3B8&langs_count=6&hide=jupyter%20notebook&hide=jupyter%20notebook" alt="Top Languages" width="60%" />

</div>

---

## 🐍 Contribution Activity

<div align="center">

<img src="https://raw.githubusercontent.com/SiririComun/SiririComun/output/github-contribution-grid-snake-dark.svg" alt="Contribution Snake Animation" width="100%" />

</div>

---

## 🎛️ Tech Stack & Ecosystem

<div align="center">

<img src="https://skillicons.dev/icons?i=c,cpp,cuda,python,bash,linux,docker,git,githubactions,postgres,redis,latex" />

<br><br>

| Layer | Technologies & Hardware |
| :--- | :--- |
| **Silicon & Logic (RTL)** | **VHDL-93/2008**, Verilog, AMD Vivado, Hog (HDL on Git), GHDL, Zynq-7000 SoC, AXI4-Stream, CORDIC, LogiCORE FFT/IFFT |
| **Co-Design & Linux** | **PYNQ-Z2**, Multi-Channel AXI DMA (Concurrent 3-DMA), Zero-Copy CMA, Hardware Triggering, Linux Drivers |
| **HPC & Simulation** | **C++17 (Data-Oriented Design)**, CUDA (Warp-Shuffle), OpenMP, Monte Carlo, Numerov Solvers, Photonic Crystals |
| **Tooling & Automation** | **Zero-Dependency CLI Tools**, PyMuPDF, AST/Regex Compaction, Docker HPC Passthrough, Redis HA |

</div>

---

## 🚀 Featured Systems & Repositories

### ⚡ FPGA Hardware & PYNQ Ecosystem

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>⚡ <a href="https://github.com/SiririComun/hw-xadc-dma-overlays">HW XADC DMA Overlays</a></h3>
      <p><i>Core Vivado Hardware Overlays (VHDL & RTL)</i></p>
      <ul>
        <li><b>Dual Parallel Sampling:</b> Synchronous XADC acquisition with phase-locked hardware triggering.</li>
        <li><b>Hardware DSP:</b> Real-time Hermitian spectral filter, decimation, and IFFT time reconstruction.</li>
        <li><b>3-DMA Streaming:</b> Concurrent raw time, FFT spectrum, and filtered audio direct to DDR.</li>
      </ul>
      <img src="https://img.shields.io/badge/VHDL-Vivado-orange?style=flat-square"> <img src="https://img.shields.io/badge/AXI4--Stream-DMA-blue?style=flat-square"> <img src="https://img.shields.io/badge/Hog-HDL_on_Git-purple?style=flat-square">
    </td>
    <td width="33%" valign="top">
      <h3>📈 <a href="https://github.com/SiririComun/sw-pynq-oscilloscope">PYNQ Lab Oscilloscope</a></h3>
      <p><i>Multi-Regime Scope & Signal Analyzer</i></p>
      <ul>
        <li><b>Multi-Regime Profiles:</b> Dynamic switching across Wideband Scope, Full Audio, and Deep Bass regimes.</li>
        <li><b>Signal Generation:</b> Integrated Analog Discovery 3 dual wavegen for live aliasing exploration.</li>
        <li><b>Interactive Filter Dashboard:</b> 4-trace multi-domain UI for live frequency cutoff tuning.</li>
      </ul>
      <img src="https://img.shields.io/badge/Python-PYNQ-green?style=flat-square"> <img src="https://img.shields.io/badge/Plotly-Dashboard-blue?style=flat-square"> <img src="https://img.shields.io/badge/AD3-Wavegen-orange?style=flat-square">
    </td>
    <td width="33%" valign="top">
      <h3>🎙️ <a href="https://github.com/SiririComun/sw-pynq-sound-localizer">PYNQ Sound Localizer</a></h3>
      <p><i>Acoustic Kinematics & Doppler Tracker</i></p>
      <ul>
        <li><b>Doppler Telemetry:</b> Sub-Hertz fundamental pitch tracking ($20\text{ Hz} - 20\text{ kHz}$) and radial velocity estimation.</li>
        <li><b>Dual-Telemetry GUI:</b> 10-second rolling two-thread dashboard for simultaneous amplitude and pitch curves.</li>
        <li><b>Flight Recorder:</b> Multi-second continuous flight recording directly to DDR memory.</li>
      </ul>
      <img src="https://img.shields.io/badge/Python-PYNQ-green?style=flat-square"> <img src="https://img.shields.io/badge/Acoustics-Doppler-teal?style=flat-square"> <img src="https://img.shields.io/badge/Kinematics-Telemetry-blue?style=flat-square">
    </td>
  </tr>
</table>

### 🧠 High-Performance Computing, Developer Tooling & Security

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>🚀 <a href="https://github.com/SiririComun/Ising-Dynamics">Ising-Dynamics HPC Engine</a></h3>
      <p><i>Massively Parallel GPU Physics Engine</i></p>
      <ul>
        <li><b>GPU Acceleration:</b> High-throughput Monte Carlo simulation using Red-Black Checkerboard SIMT and warp-shuffle reductions.</li>
        <li><b>Statistical Validation:</b> Finite-Size Scaling critical exponent extraction and Fluctuation-Dissipation analysis.</li>
        <li><b>Reproducible Environment:</b> Fully containerized CUDA Docker setup.</li>
      </ul>
      <img src="https://img.shields.io/badge/CUDA-C%2B%2B17-00599C?style=flat-square"> <img src="https://img.shields.io/badge/Docker-HPC-blue?style=flat-square">
    </td>
    <td width="33%" valign="top">
      <h3>🧠 <a href="https://github.com/SiririComun/Cog">Cog — Context on Git</a></h3>
      <p><i>Token-Optimized LLM Context Compactor</i></p>
      <ul>
        <li><b>Zero External Dependencies:</b> High-performance cross-platform CLI and Git submodule engine.</li>
        <li><b>Domain Slicing:</b> AST/regex surgical compaction for Vivado Block Designs, XDC, TCL, C++, and Notebooks.</li>
        <li><b>Audit & PR Review:</b> Calibrated token estimation and automated PR review diff generation.</li>
      </ul>
      <img src="https://img.shields.io/badge/CLI-Engine-cyan?style=flat-square"> <img src="https://img.shields.io/badge/LLM-Context_Tool-yellow?style=flat-square">
    </td>
    <td width="33%" valign="top">
      <h3>🛡️ <a href="https://github.com/SiririComun/aligo-c2-frameworkk">ALIGO C2 Framework</a></h3>
      <p><i>Distributed High-Availability Security System</i></p>
      <ul>
        <li><b>Hybrid Cryptography:</b> RSA-2048 key exchange + Fernet AES-128-CBC payload encryption.</li>
        <li><b>Smart HA Watchdog:</b> Automated background failover across multiple nodes and Redis synchronization.</li>
        <li><b>Hackathon Finalist:</b> Engineered for the 24-hour regional Talento Tech security track.</li>
      </ul>
      <img src="https://img.shields.io/badge/Security-C2-crimson?style=flat-square"> <img src="https://img.shields.io/badge/Crypto-RSA_%2B_AES-green?style=flat-square">
    </td>
  </tr>
</table>

---

## 🏆 Research Appointments & Honors

```text
• 🔬 Junior Researcher  ──► Scientific Instrumentation & Microelectronics Group (GICM - UdeA, COL0012589)
• 🔬 Junior Researcher  ──► Biophysics Group (Photonic crystals & biological electromagnetic modeling)
• 🏆 Hackathon Finalist ──► Talento Tech Regional 24h Challenge (Cybersecurity & C2 Systems)
• 🥈 2nd Place Winner   ──► XIV Experimental Physics Showcase (Advanced Category — Lenz's Law)
• 📜 Data Certified     ──► MinTIC / UdeA (159 Hours) • EF SET English Certified (B1/B2 Speaking)
```

---

## ♟️ Beyond Code

* ♟️ **Competitive Chess:** FIDE Rated **2000+ Elo**. I apply competitive chess thinking to systems engineering—deep tree evaluation, structural risk analysis, bottleneck anticipation, and tactical execution.
* 📐 **Complex Origami:** Algorithmic crease pattern design and 3D spatial geometry.

---

<div align="center">
  <sub>⚡ Built with precision across VHDL, C++17, CUDA & Open Automation</sub>
</div>