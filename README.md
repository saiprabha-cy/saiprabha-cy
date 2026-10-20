<!-- =========================================================
     SAI PRABHA C Y — GITHUB PROFILE README
     Repository: github.com/saiprabha-cy/saiprabha-cy
     ========================================================= -->

<div align="center">

# SAI PRABHA C Y

### Embedded Systems · Firmware · Avionics · Aerospace

**Building embedded and aerospace systems from design through validation.**

<br>

<a href="https://saiprabha-cy.github.io">
  <img src="https://img.shields.io/badge/🌐_Portfolio-saiprabha--cy.github.io-111827?style=for-the-badge" alt="Portfolio">
</a>
<a href="https://www.linkedin.com/in/saiprabha-c-y">
  <img src="https://img.shields.io/badge/LinkedIn-Profile-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>
<a href="https://github.com/saiprabha-cy">
  <img src="https://img.shields.io/badge/GitHub-Projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</a>

</div>

---

<div align="center">

**[ 🚀 Projects ](#-engineering-projects) ·
[ ⚙️ Systems ](#-engineering-focus) ·
[ 📡 Research ](#-research) ·
[ ✍️ Writing ](#-technical-writing) ·
[ 🛰️ Space ](#-space--aerospace-work) ·
[ 🌐 Portfolio ](https://saiprabha-cy.github.io)**

</div>

---

## `> whoami`

I am an **Electronics & Communication Engineering graduate** focused on developing practical skills across:

- Embedded Systems
- Firmware Development
- Avionics & Telemetry
- Aerospace Electronics
- Flight Computers
- Communication Systems
- Aerospace Simulation & GNC
- PCB / Hardware Validation
- RTL / Digital Design

My approach is to move beyond isolated software projects and understand the complete engineering chain:

**requirements → architecture → implementation → interface → validation**

---

## ⚙️ ENGINEERING FOCUS

<table>
<tr>
<td width="25%" align="center">

### 🧠 Embedded

C / C  
STM32  
Bare-Metal  
Drivers  
UART / SPI / I²C

</td>

<td width="25%" align="center">

### 📡 Avionics

Telemetry  
Flight Computers  
Packet Protocols  
FDIR  
Sensor Interfaces

</td>

<td width="25%" align="center">

### 🚀 Aerospace

GNC  
Flight Simulation  
CubeSat Systems  
Mission Operations  
OpenRocket

</td>

<td width="25%" align="center">

### 🔧 Hardware

KiCad  
PCB Design  
Schematic Design  
Hardware Validation  
RTL / FPGA

</td>
</tr>
</table>

---

# 🚀 ENGINEERING PROJECTS

> A selection of systems I have designed, implemented, simulated, or documented.

### 🛰️ 01 — Integrated Launch Vehicle & Satellite GNC Digital Twin

**Launch-vehicle ascent → insertion → satellite mission simulation**

`MATLAB` `Python` `GNC` `Simulation`

A digital-twin style aerospace simulation environment covering mission initialization, launch/ascent logic and orbital insertion concepts.

**Repository →**  
[🔗 Launch-Vehicle-Ascent-Insertion-GNC-Digital-Twin](https://github.com/saiprabha-cy/Launch-Vehicle-Ascent-Insertion-GNC-Digital-Twin)

---

### 🛰️ 02 — CubeSat OBC / Telemetry Simulator

**Onboard computer architecture → telemetry → fault handling**

`C` `Python` `Telemetry` `OBC` `FDIR`

A software-based CubeSat onboard-computer environment developed to study telemetry generation, packet handling, system states and fault-response concepts before moving toward hardware implementation.

<details>
<summary><b>▶ Explore the architecture</b></summary>

```text
                 ┌─────────────────────┐
                 │     Sensor Inputs   │
                 └──────────┬──────────┘
                            ↓
                 ┌─────────────────────┐
                 │     Flight Logic    │
                 └──────────┬──────────┘
                            ↓
                 ┌─────────────────────┐
                 │ Telemetry Formatter │
                 └──────────┬──────────┘
                            ↓
                 ┌─────────────────────┐
                 │ Packet / Downlink   │
                 └─────────────────────┘
                            ↑
                 ┌─────────────────────┐
                 │       FDIR          │
                 └─────────────────────┘
```

</details>

---

### 🤖 03 — Planetary Rover Autonomous Navigation & Mapping

**Autonomous navigation → mapping → planetary robotics**

`Python` `Robotics` `Navigation` `Mapping`

A focused simulation project exploring autonomous rover navigation and mapping concepts for planetary environments.

**Repository →**  
[🔗 Planetary Rover Navigation & Mapping](https://github.com/saiprabha-cy)

---

### 🔧 04 — Aerospace Hardware Validation Platform

**KiCad → schematic architecture → PCB validation**

`KiCad` `STM32` `PCB` `Hardware`

Aerospace-oriented hardware design work focused on hierarchical schematics, MCU interfaces, power/interface planning and validation-oriented PCB design.

<details>
<summary><b>▶ Hardware design philosophy</b></summary>

```text
Requirements
     ↓
System Architecture
     ↓
Hierarchical Schematic
     ↓
Component Selection
     ↓
PCB Layout
     ↓
ERC / DRC
     ↓
Design Review
     ↓
Hardware Validation
```

</details>

---

### 📡 05 — Intelligent Propagation-Aware Satellite Communication

**Propagation modelling → satellite communication → intelligent prediction**

`Python` `Machine Learning` `Satellite Communication`

Research-oriented work exploring propagation-aware modelling for satellite communication systems.

**Repository →**  
[🔗 Intelligent Propagation-Aware Satcom](https://github.com/saiprabha-cy/Intelligent-propagation-aware-satcom)

---

### 💻 06 — Telemetry Packet Parser — RTL

**Packet framing → FSM → CRC validation**

`Verilog` `RTL` `FSM` `CRC` `Icarus Verilog` `GTKWave`

A digital-design project exploring implementation of a telemetry packet parser as synthesizable-style RTL logic.

<details>
<summary><b>▶ Packet-processing concept</b></summary>

```text
        Incoming Bitstream
                │
                ▼
        ┌───────────────┐
        │ Synchronization│
        └───────┬───────┘
                ▼
        ┌───────────────┐
        │ Header Detect │
        └───────┬───────┘
                ▼
        ┌───────────────┐
        │ Payload State │
        └───────┬───────┘
                ▼
        ┌───────────────┐
        │  CRC Check    │
        └───────┬───────┘
                ▼
          VALID / ERROR
```

</details>

---

# 🧩 ENGINEERING STACK

<details>
<summary><b>▶ Embedded Systems & Firmware</b></summary>

- Embedded C
- C fundamentals
- STM32
- ARM Cortex-M
- Bare-metal programming
- Register-level concepts
- GPIO
- Timers
- UART
- SPI
- I²C
- Interrupts
- Driver development
- Debugging

</details>

<details>
<summary><b>▶ Aerospace & Simulation</b></summary>

- MATLAB
- Simulink
- Python
- OpenRocket
- OpenVSP
- XFLR5
- Flight dynamics
- GNC concepts
- Telemetry
- Mission operations
- CubeSat systems

</details>

<details>
<summary><b>▶ Hardware & Digital Design</b></summary>

- KiCad
- Schematic capture
- PCB design
- ERC / DRC
- Hardware interfaces
- STM32 MCU architecture
- RTL fundamentals
- Verilog
- FSM design
- CRC logic
- Icarus Verilog
- GTKWave
- Yosys

</details>

<details>
<summary><b>▶ Communication & Research</b></summary>

- Digital communications
- Signal processing
- Satellite communications
- RF propagation modelling
- Machine learning
- Python scientific computing
- MATLAB numerical modelling

</details>

---

# 📡 RESEARCH

### Machine Learning-Based Excess Path Loss Modeling for S-Band Terrestrial Radio Propagation

Research work exploring machine-learning-based modelling of excess path loss for S-band terrestrial radio propagation.

**TechRxiv:**  
[🔗 DOI: 10.36227/techrxiv.176834562.26769030/v1](https://doi.org/10.36227/techrxiv.176834562.26769030/v1)

---

### Digital Twin Telescope

A software-oriented astronomy and digital-twin project involving astronomical data processing, telescope modelling and observation workflows.

**Related work:**  
[🌐 Portfolio](https://saiprabha-cy.github.io)

---

### DTT Research Output

[🔗 Zenodo — DOI: 10.5281/zenodo.18017921](https://doi.org/10.5281/zenodo.18017921)

---

# 🛰️ SPACE & AEROSPACE WORK

My aerospace learning has included work across:

```text
                    SPACE SYSTEMS
                         │
          ┌──────────────┼──────────────┐
          ↓              ↓              ↓
      Avionics        Simulation      Mission
          │              │            Operations
          ↓              ↓              ↓
     Telemetry          GNC         Communications
          │              │              │
          └──────────────┼──────────────┘
                         ↓
                 Systems Engineering
```

### Experience & Training

**Electronics Engineering Intern — MacroEdTech**

Remote engineering work involving educational electronics, aerospace documentation and CubeSat-oriented technical work.

**BSERC Def-Space Winter Internship**

Projects included:

- VTOL / drone air-taxi concept
- Aircraft design studies
- MATLAB-based analysis
- OpenVSP / XFLR5 exploration
- Water-rocket modelling
- OpenRocket

---

# 🔬 CITIZEN SCIENCE

Space science is also part of my practical learning outside conventional engineering projects.

### Astronomy / Citizen Science

- Asteroid classification
- Variable-star observations
- Galaxy classification
- Space-science data analysis
- Preliminary transient/detection work

Projects and participation include platforms such as NASA / ESA / NAOJ citizen-science initiatives and IASC-related astronomy work.

---

# ✍️ TECHNICAL WRITING

I document engineering concepts while learning them.

### Featured

**What Actually Happens When You Call `HAL_GPIO_WritePin()`?**

A low-level exploration of what happens between an application-level GPIO call and the underlying MCU hardware.

**More technical articles →**  
[📝 Medium](https://medium.com/)

---

# 📊 GITHUB ACTIVITY

<div align="center">

<a href="https://github.com/saiprabha-cy">

<img src="https://github-readme-stats.vercel.app/api?username=saiprabha-cy&show_icons=true&hide_border=true&rank_icon=github&include_all_commits=true&count_private=false" height="165" alt="GitHub statistics">

</a>

<a href="https://github.com/saiprabha-cy">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=saiprabha-cy&layout=compact&hide_border=true&langs_count=8" height="165" alt="Top languages">

</a>

</div>

<br>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=saiprabha-cy&hide_border=true" alt="GitHub contribution streak">

</div>

---

# 🧭 CURRENT ENGINEERING DIRECTION

```text
                 EMBEDDED SYSTEMS
                        │
             ┌──────────┴──────────┐
             ↓                     ↓
          Firmware              Hardware
             │                     │
             ↓                     ↓
          STM32                 KiCad
             │                     │
             └──────────┬──────────┘
                        ↓
                    AVIONICS
                        │
             ┌──────────┼──────────┐
             ↓          ↓          ↓
         Telemetry     OBC       Interfaces
             │          │          │
             └──────────┼──────────┘
                        ↓
                    AEROSPACE
                        │
             ┌──────────┼──────────┐
             ↓          ↓          ↓
            GNC     Simulation   Mission Ops
```

---

# 🎯 WHAT I'M BUILDING TOWARD

**Embedded Systems → Firmware → Avionics → Aerospace Systems**

The goal is to develop the ability to work across the boundary between:

> **software + electronics + communication + aerospace systems**

rather than treating these as isolated disciplines.

---

# 🌐 EXPLORE MORE

<div align="center">

### Full Engineering Portfolio

<a href="https://saiprabha-cy.github.io">
<img src="https://img.shields.io/badge/OPEN_PORTFOLIO-111827?style=for-the-badge&logo=googlechrome&logoColor=white">
</a>

### GitHub Projects

<a href="https://github.com/saiprabha-cy?tab=repositories">
<img src="https://img.shields.io/badge/EXPLORE_REPOSITORIES-181717?style=for-the-badge&logo=github&logoColor=white">
</a>

### LinkedIn

<a href="https://www.linkedin.com/in/saiprabha-c-y">
<img src="https://img.shields.io/badge/CONNECT_ON_LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
</a>

</div>

---

<div align="center">

**Embedded Systems | Firmware | Avionics | Aerospace**

*Engineering through understanding, implementation, and validation.*

</div>
