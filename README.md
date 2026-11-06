<h1 align="center">Hi, I'm Jayanta Chakraborty 👋</h1>

<p align="center">
  <b>Electronics & Communication Engineering student | VLSI & ASIC Design Enthusiast</b><br>
  Turning RTL into silicon, from transistor-level design to GDSII.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN-ID"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:jc2729@ece.jgec.ac.in"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## 🧑‍💻 About Me

- 🎓 4th-year B.Tech student in **Electronics and Communication Engineering** at **Jalpaiguri Government Engineering College** (2023–2027), CGPA **8.93** through 3rd year
- 🏅 **2nd rank in academics** for the 2025–26 session
- 🔬 Summer intern at the **Microelectronics Technology and VLSI Design Lab, Jadavpur University** (2025)
- 🚦 Participant in **Smart India Hackathon 2024**, where I built an AI-driven intelligent traffic management solution
- 📍 Based in West Bengal, India

---

## 🛠️ Tech Stack & Skills

**Languages**

![Verilog](https://img.shields.io/badge/Verilog-1F425F?style=flat-square)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-005C8F?style=flat-square)
![TCL](https://img.shields.io/badge/TCL-E4CC98?style=flat-square&logoColor=black)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Embedded C](https://img.shields.io/badge/Embedded%20C-444444?style=flat-square)

**ASIC / EDA Tools**

![Yosys](https://img.shields.io/badge/Yosys-2E7D32?style=flat-square)
![OpenLane2](https://img.shields.io/badge/OpenLane2-1565C0?style=flat-square)
![OpenROAD](https://img.shields.io/badge/OpenROAD-6A1B9A?style=flat-square)
![OpenSTA](https://img.shields.io/badge/OpenSTA-AD1457?style=flat-square)
![Magic](https://img.shields.io/badge/Magic-EF6C00?style=flat-square)
![KLayout](https://img.shields.io/badge/KLayout-00838F?style=flat-square)
![Cadence Virtuoso](https://img.shields.io/badge/Cadence%20Virtuoso-C62828?style=flat-square)
![Xilinx Vivado](https://img.shields.io/badge/Xilinx%20Vivado-F57C00?style=flat-square)
![LTSpice](https://img.shields.io/badge/LTSpice-455A64?style=flat-square)
![SKY130 PDK](https://img.shields.io/badge/SkyWater%20SKY130-37474F?style=flat-square)

**Design & Verification**

Micro-architecture & Datapath Design · RTL Design · Physical Design · Static Timing Analysis (multi-corner PVT) · Functional Verification · Testbench Development · DFT · CDC

---

## 🚀 Featured Projects

### 🔹 [4×4 3-Stage Pipelined MAC Unit: Datapath Design & Full ASIC Flow](https://github.com/GithubJayanta/MAC_unit_4bit) &nbsp;`July 2026`
A 3-stage pipelined multiply-accumulate datapath in structural Verilog, with a custom **Wallace Tree multiplier** and a **12-bit carry-look-ahead adder** built from gate-level primitives.
- Full **RTL-to-GDSII** flow on **SkyWater SKY130**: Yosys → OpenLane2/OpenROAD → OpenSTA → Magic/KLayout
- Closed at **223 standard cells / 28 flip-flops** with a DRC/LVS-clean layout
- **Multi-corner STA** across 9 PVT×RC corners, with zero setup/hold violations and 227.55–735.11 MHz against a 200 MHz target
- Self-checking golden-reference testbench

`Verilog` `Yosys` `OpenLane2` `OpenROAD` `OpenSTA` `Magic` `KLayout` `SKY130`

### 🔹 [Custom 4-bit Wallace Tree Multiplier: Transistor-Level IP Core](https://github.com/GithubJayanta/Custom_Wallace_Tree_Multiplier_IP) &nbsp;`June 2026`
A 4-bit Wallace Tree multiplier designed **entirely at the transistor level** in Cadence Virtuoso, with no RTL and no synthesis tool. Partial-product generation, half/full adders and a CLA were built by hand across 63 gates / 828 transistors in 90 nm CMOS.
- Functional correctness of **90–95%** verified through transient simulation, with waveform-level debug separating real failures from switching glitches
- Hand-characterized PPA:

| Metric | Result |
|---|---|
| Avg. dynamic power | 2.22 µW |
| Critical combinational delay | 395 ps |
| Min. clock period | 495.691 ps (≈ 2.02 GHz) |
| Power-delay product | 0.877 fJ |
| Est. silicon area | 134–201 µm² |

`Cadence Virtuoso` `90 nm CMOS` `Transistor-level design` `PPA analysis`

### 🔹 [High-Speed 4-bit Kogge-Stone Adder: Micro-Architecture & PPA Analysis](https://github.com/GithubJayanta/4-Bit_Kogge_Stone_Adder) &nbsp;`June 2026`
A parallel-prefix Kogge-Stone adder in Verilog, built as a comparative study against ripple-carry for high-speed arithmetic.
- Synthesized with Yosys and taken through physical implementation with **0 DRC / 0 LVS violations**
- **3.244 ns** post-layout critical path, **19.37 µW** power, **217.7 µm²** area
- Quantified where the O(log₂ n) delay advantage pays off against physical-design overhead at small bit-widths

`Verilog` `Yosys` `Physical Design` `Kogge-Stone` `PPA`

---

## 💼 Experience

**Summer Intern, Microelectronics Technology and VLSI Design Lab, Jadavpur University** &nbsp;`Jun – Jul 2025`
- Designed digital datapath blocks in Verilog (a multiplexed 4-digit 7-segment display controller and a 4-bit shift register) and deployed them on FPGA through the **Xilinx Vivado** RTL-to-bitstream flow
- Built custom CMOS standard-cell layouts (NAND/NOR) in **Cadence Virtuoso**
- Designed and simulated a **MOS differential amplifier**
- Got hands-on exposure to semiconductor fabrication: wafer cleaning, thermal oxidation, photolithography and etching

---

## 🔭 What I'm Exploring Next

- 🧩 **Design for Test (DFT):** scan insertion, ATPG and testability-aware design
- 🔀 **Clock Domain Crossing (CDC):** safe multi-clock design and verification
- ⚙️ **Advanced Physical Design:** floorplanning, power planning, CTS and timing closure at larger scale
- 🧪 **Design Verification:** SystemVerilog-based testbenches and verification methodology
- 🌐 **Open-source silicon:** more open-PDK and open-EDA tapeout-oriented projects
- 🧠 **Hardware accelerators:** pipelined and parallel arithmetic datapaths for compute-heavy workloads

---

## 🎓 Education

| Institution | Program | Period |
|---|---|---|
| Jalpaiguri Government Engineering College | B.Tech, ECE (CGPA 8.93 through 3rd year) | 2023 – 2027 |

**Relevant coursework:** Computer Architecture · VLSI Design · CMOS Technology · RTL Design · Static Timing Analysis · Layout Design · Analog & Digital Electronics

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=GithubJayanta&show_icons=true&theme=default&hide_border=true" alt="GitHub stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=GithubJayanta&layout=compact&hide_border=true" alt="Top languages" />
</p>

---

## 📫 Let's Connect

I'm open to **VLSI / ASIC design internships and collaborations**. Feel free to reach out at **jc2729@ece.jgec.ac.in** or on [LinkedIn](www.linkedin.com/in/jayanta-chakraborty-6625aa28a).

<p align="center"><i>⚡ From transistors to timing closure, one design at a time.</i></p>
