7.9 GHz SIW Slot Antenna – ANSYS HFSS

📡 Project Overview

This project presents the design and electromagnetic simulation of a Substrate Integrated Waveguide (SIW) slot antenna operating around 7.9 GHz using ANSYS HFSS.

The antenna is implemented on an RT/Duroid™ substrate with relative permittivity εr = 2.2 and excited through a microstrip feed.

The design was developed in two stages: an initial configuration was evaluated first, followed by geometric modification near the feed region to improve impedance matching.

---

🎯 Project Goals

- Design an SIW slot antenna for operation near 7.9 GHz.
- Model the antenna structure in ANSYS HFSS.
- Evaluate the initial antenna performance.
- Improve impedance matching through geometric modification.
- Compare the initial and optimized configurations.
- Analyze S11 / return loss.
- Study electric and magnetic field distributions.
- Examine surface-current distribution.
- Evaluate the simulated radiation characteristics.

---

🛠️ Tools & Materials

Parameter| Details
Simulation Software| ANSYS HFSS
Antenna Type| SIW Slot Antenna
Operating Frequency| ~7.9 GHz
Substrate| RT/Duroid™
Relative Permittivity| εr = 2.2
Feeding Method| Microstrip Feed
Analysis| Full-wave EM Simulation
Optimization| Slot Geometry

---

📐 Design Approach

The antenna was initially modeled with an SIW structure coupled to a slot and microstrip feed.

The initial configuration was simulated to determine its resonant behavior and impedance matching.

The results showed that although the antenna resonated close to the desired frequency, the impedance matching was not sufficiently strong. This motivated a second design iteration.

Initial Configuration

The initial model provided the baseline for evaluating the effect of the subsequent geometric modification.

The simulated return loss was approximately −2.2 dB near 7.9 GHz, indicating poor impedance matching.

Optimized Configuration

Two additional tuning slots were introduced near the microstrip feed region.

This modification changes the electromagnetic behavior around the feed and improves the coupling and impedance matching of the antenna while maintaining operation near the target frequency.

---

🔄 Optimization Process

The optimization can be summarized as:

Initial SIW Slot Antenna
          ↓
Full-Wave HFSS Simulation
          ↓
Analyze S11 / Resonance
          ↓
Identify Poor Impedance Matching
          ↓
Introduce Feed-Region Tuning Slots
          ↓
Re-simulate
          ↓
Optimized SIW Slot Antenna

This comparison demonstrates how relatively small geometric changes can influence the impedance characteristics of a microwave antenna.

---

📊 Simulation Results

The optimized antenna was evaluated using full-wave electromagnetic simulation in ANSYS HFSS.

The analysis includes:

- S11 / Return Loss
- Electric Field Distribution
- Magnetic Field Distribution
- Surface Current Distribution
- Radiation Characteristics

The optimized configuration achieves a simulated minimum return loss of approximately:

S11 ≈ −16.38 dB

near the intended 7.9 GHz operating region.

This represents a substantial improvement compared with the initial configuration.

---

📈 Performance Comparison

Configuration| Operating Region| Minimum Return Loss
Initial Design| ~7.9 GHz| ≈ −2.2 dB
Optimized Design| ~7.9 GHz| ≈ −16.38 dB

The comparison demonstrates the improvement in impedance matching obtained through the additional feed-region tuning slots.

---

⚡ Electromagnetic Analysis

S11 / Return Loss

S11 is used to evaluate the amount of input power reflected from the antenna.

A more negative S11 value indicates improved impedance matching at the corresponding frequency.

Electric Field

The electric-field distribution provides insight into how electromagnetic energy is established and propagated through the SIW structure and slot region.

Magnetic Field

The magnetic-field distribution helps visualize the electromagnetic behavior inside and around the SIW cavity and radiating region.

Surface Current

Surface-current visualization shows how current flows across the conducting portions of the antenna and helps explain the radiating behavior.

Radiation Characteristics

The simulated radiation characteristics provide information about how the antenna distributes electromagnetic energy into free space.

---

📁 Repository Structure

7.9GHz-SIW-Slot-Antenna-HFSS/
│
├── HFSS_Project/
│   └── HFSS design files
│
├── Simulation_Results/
│   └── electromagnetic simulation outputs
│
├── Antenna_specifications.png
├── Design_parameters.png
├── Initial Design.png
├── Final_Optimized_Design.png
├── Key_Performance_Summary_Table.png
│
├── LICENSE
└── README.md

---

🧠 Skills Demonstrated

- SIW Antenna Design
- ANSYS HFSS
- RF & Microwave Engineering
- Full-Wave Electromagnetic Simulation
- Antenna Geometry Optimization
- Impedance Matching
- S11 / Return Loss Analysis
- Electric-Field Analysis
- Magnetic-Field Analysis
- Surface-Current Analysis
- Radiation Analysis
- Microwave Antenna Modeling

---

💡 Applications

SIW-based antennas are relevant to areas such as:

- Microwave communication
- Radar and sensing
- High-frequency wireless systems
- SIW component research
- RF front-end development
- Antenna and electromagnetic research

---

📚 Key Learning Outcomes

This project provides practical experience with:

- Modeling microwave antennas in HFSS
- Understanding SIW-based antenna structures
- Evaluating impedance matching
- Interpreting S11 results
- Performing geometry-based optimization
- Visualizing electromagnetic fields
- Understanding surface-current behavior
- Comparing baseline and optimized antenna designs

---

📌 Project Summary

Antenna: SIW Slot Antenna
Target Frequency: ~7.9 GHz
Substrate: RT/Duroid™
εr: 2.2
Software: ANSYS HFSS
Optimization: Feed-region tuning slots
Optimized S11: ≈ −16.38 dB

---
