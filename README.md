# Hi, I'm Joy Huang 👋

## Robotics, Controls & Mechatronics Engineer

Final-year Mechanical Engineering MEng student at Imperial College London, building and validating systems across the mechanism–motor–sensor–firmware–control boundary. My focus is reliable robotics, embedded control and intelligent electromechanical systems, with a growing specialisation in medical and surgical robotics.

**Embedded C · Python · C++ (developing) · control & PID · microcontrollers · I²C/UART · CAD · experimental validation**

## Featured projects

### Design, Make & Test — Closed-Loop Electromechanical Wrapping System
**Mechanical design · Arduino Nano Every · Raspberry Pi 5 · DC motor control · Hall-effect sensing · PID control · experimental validation**

Developed and experimentally validated, in a four-person engineering team, an intelligent wrapping subsystem for an automated core–shell yarn machine intended to support wearable-electronics and biomedical-sensing research.

The subsystem combines a 30 W hollow-shaft DC motor, rotating arm, removable shell-yarn spool, passive eddy-current damping, Hall-effect speed feedback, Arduino control, and Raspberry Pi logging. The final tuned controller achieved stable operation at normal speeds while meeting the key speed-response targets.

<p align="center">
  <img src="https://raw.githubusercontent.com/Jo-YuHuang/closed-loop-electromechanical-wrapping-system/main/docs/assets/final-cad-model.png" alt="Final CAD model of the complete wrapping machine" width="820">
</p>
<p align="center"><em>Final CAD model of the complete enclosed machine.</em></p>

**Test highlights:** **0.176%** average steady-state error · **0.237 s** settling time · **0.44%** maximum Hall-sensor error against a laser tachometer · stable testing to **3,000 RPM** · no dominant structural resonance near the **41.7 Hz** operating frequency.

[View the full project repository, CAD, testing evidence and validation results →](https://github.com/Jo-YuHuang/closed-loop-electromechanical-wrapping-system)

### Autonomous Embedded Systems Buggy — Embedded C / PIC18
**Embedded C · PIC microcontroller · PWM · I²C · UART**

Designed and implemented an autonomous robotic buggy in Embedded C on a PIC microcontroller, integrating motor control, colour sensing, and navigation logic. Developed PWM-based motion control and a calibrated RGB-sensor pipeline over I²C, including ambient-light subtraction, normalisation, and threshold-based classification.

Used UART logging to calibrate sensor thresholds and collaborated in a two-person team using GitHub for parallel development and integration. The buggy achieved top-tier performance in final testing, demonstrating reliable system integration.

<p align="center">
  <img src="https://raw.githubusercontent.com/Jo-YuHuang/autonomous-buggy-navigation/main/docs/assets/project_diagram.png" alt="Autonomous buggy system diagram" width="720">
</p>
<p align="center"><em>Autonomous buggy system architecture and sensor/control integration.</em></p>

[View the personal project repository →](https://github.com/Jo-YuHuang/autonomous-buggy-navigation)

### Supporting engineering projects

#### Python Numerical Simulation Project
**Python · reaction-diffusion PDEs · numerical methods · data analysis**

Developed a Python model of bacterial colonisation using reaction-diffusion partial differential equations. Ran numerical simulations across varying spatial resolutions and analysed convergence behaviour.

Produced plots and density heatmaps to evaluate model behaviour and communicate results clearly, strengthening skills in numerical modelling, data analysis, and engineering interpretation of simulated results.

[View the Python simulation repository →](https://github.com/Jo-YuHuang/bacterial-colonisation-reaction-diffusion)


#### Autonomous Lighting Controller — Embedded C / PIC18
**Embedded C · ADC · LDR · software clock**

Designed and implemented a fully autonomous outdoor-lighting controller in Embedded C. An LDR and ADC detect ambient light and identify sunrise and sunset, while averaged adaptive thresholds and hysteresis provide robust switching behaviour.

Implemented a sun-synchronised software clock with drift correction, daylight-saving-time handling, and leap-year logic. The code was structured modularly for maintainability and long-term reliability.

[View the personal project repository →](https://github.com/Jo-YuHuang/energy-saving-outside-light)

#### Rope Bridge Launcher Design Project
**Pneumatic systems · projectile mechanics · CAD · design for manufacture · workshop manufacture · risk assessment**

Designed and manufactured, as the **Projectile Engineer** in a five-person Imperial College London team, a 1:10-scale pneumatic launcher for installing a single-rope bridge across a rainforest road in a gibbon-conservation concept. The design was selected through weighted decision matrices and developed into a workshop-manufactured prototype within a **£300 budget**.

The engineering work covered a 6 mm barbed peg, 25 J projectile-energy target, 20.5 mm pressure-cylinder bore, 6 bar compressed-air design point, O-ring sealing, centre-of-gravity placement, pressure-cylinder stress analysis, and toleranced aluminium clamp manufacture. The prototype used milling, turning, reaming, boring, grinding, laser cutting, and 3D printing across 11 manufactured parts.



**Evidence highlights:** **£276.92** prototype bill of materials · **500 N** estimated peg withdrawal force · **25 J** required projectile energy · pressure-cylinder calculation safety factor **98.8** · projectile calculation safety factor **133** · clamp measurements generally within specified tolerance.

This remains a **scaled engineering prototype**, not a field-ready wildlife or projectile system: full-scale pneumatic and projectile values, operational launch and penetration testing, noise, long-term rope behaviour, and ecological/legal deployment would require further specialist validation.

[View the full project repository, design report and engineering evidence →](https://github.com/Jo-YuHuang/rope-bridge-launcher)

## Research experience

### Medical Image Segmentation — Literature Review
**Biomedical imaging · CT · MRI · ultrasound · histopathology**

Completed an individual review of biomedical image segmentation under the supervision of Prof. Mihailo Ristic at Imperial College London. Compared classical, machine-learning and deep-learning approaches, including CNNs, FCNs and U-Net, while evaluating noise, anatomical variability, limited annotated data, generalisation and segmentation reliability for tumour and organ delineation.

The work identified research gaps and emerging hybrid approaches for robust automated segmentation in medical imaging and healthcare workflows. This was a literature-review project rather than an active software implementation project.

[Read the full literature review and research summary →](https://github.com/Jo-YuHuang/medical-image-segmentation-literature-review)

## Current development

### Robotic Manipulator Simulation — C++ & ROS 2
**C++ · ROS 2 · robotic kinematics · trajectory generation · feedback control · active development**

Building a simulated robotic manipulator in C++ and ROS 2, progressing through robot modelling, forward and inverse kinematics, Jacobian-based reasoning, trajectory generation, and feedback control.

The first public milestone will include testable requirements for position tracking, joint and velocity limits, and a controlled safe response to invalid commands or communication loss. This is an active-development project; it will be published once those simulation and verification results are available.

## Additional engineering experience

- **Imperial Formula Racing — Dyno team member:** supported dyno-related work in the engine team, gaining hands-on experience in test preparation, performance evaluation, and reliability-focused engineering.
- **Robotics competition:** led a team programming a Lego car for fast, accurate navigation through a narrow obstacle course; achieved third place at the Department of Engineering, University of Cambridge competition.

## About

My interest in healthcare is personal. Having seen close family members experience serious and long-term health problems, I have wanted to use engineering in a field where my work can make a meaningful difference to people’s lives. This became more tangible through a conversation with a surgeon about the number of patients waiting for treatment and the limited number of procedures a surgeon can perform each day. Hearing how surgical robotics could improve efficiency and help more patients receive treatment showed me how software, control and physical-system engineering could contribute to a healthcare challenge I genuinely care about.

My interest in robotics began during my A-levels, when I led a team in a robotics competition at the University of Cambridge and achieved third place. I enjoyed seeing software, mechanics and control come together to make a physical system behave intelligently. At Imperial College London, my interests in healthcare and robotics have increasingly converged into a clear ambition to work in medical and surgical robotics.

I have shaped my final year around this direction through Robot Dynamics & Control, Advanced Control, Machine Learning, Robotic Manipulators & Automation Technology, and a year-long medical robotics research project at Imperial’s Hamlyn Centre for Robotic Surgery. Alongside this academic direction, my engineering projects have given me hands-on experience at the interface between software and physical systems.

## Technical focus

- Embedded C, Python, MATLAB; C++ (developing)
- PIC18F67K40, Arduino, DC motor control, PID control, PWM, ADC and sensor integration
- I²C, UART, Git and GitHub
- ROS 2 (developing), robot control and numerical modelling
- SolidWorks, mechanical design, mechanism design, engineering drawings and experimental testing

---

This profile is a focused portfolio of software, embedded, robotics, medical-technology, and engineering projects.
