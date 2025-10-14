⚡** Design and Simulation of a High-Efficiency SiC-Based Dual Active Bridge DC–DC Converter
with Single Phase Shift (SPS) Control for EV Battery Charging** //
📘 Overview

This project presents the design and simulation of a Silicon Carbide (SiC)-based Dual Active Bridge (DAB) DC–DC converter for Electric Vehicle (EV) battery charging applications. The converter operates using Single Phase Shift (SPS) control to regulate bidirectional power flow between the source and the battery.

By utilizing SiC MOSFETs, the system achieves higher switching frequencies, lower conduction losses, and improved efficiency compared to conventional silicon-based designs. The proposed converter demonstrates compactness, reliability, and exceptional energy conversion performance suited for next-generation EV chargers.

🎯 Objectives

Develop a SiC-based Dual Active Bridge converter model in MATLAB/Simulink.

Implement the Single Phase Shift (SPS) control strategy for efficient power regulation.

Optimize leakage inductance and switching parameters to achieve maximum efficiency.

Integrate a Constant Current–Constant Voltage (CC–CV) charging algorithm for stable battery charging.

Validate the design through simulation results and planned hardware implementation.

⚙️ System Configuration
Parameter	Description
Input Voltage	400 V DC
Battery Voltage	60 V (Nominal), 120 Ah
Switching Frequency	50 kHz
Transformer Rating	1 kVA, Turns Ratio 6.67:1
Leakage Inductance	95 µH
Input/Output Capacitance	1200 µF each
🔋 Working Principle

The DAB converter transfers power by controlling the phase shift between primary and secondary bridge voltages.

Positive phase shift → power flows from source to battery (charging).

Negative phase shift → power flows in the opposite direction (discharging).
The SPS control maintains simplicity and enables bidirectional power flow with near Zero-Voltage Switching (ZVS) conditions, ensuring reduced switching losses and improved reliability.

📊 Simulation Highlights

Developed and simulated in MATLAB/Simulink.

Achieved efficiency up to 96.78% with optimized inductor design (95 µH).

Delivered 4.1 kW power output at a phase shift of 63°.

Maintained stable 60 V output and continuous inductor current in triangular waveform.

✅ Key Outcomes

Demonstrated the feasibility of SiC-based DAB converters for high-efficiency EV charging.

Validated the effectiveness of SPS control for bidirectional energy transfer.

Achieved significant efficiency gains and reduced thermal losses compared to traditional silicon converters.

🚀 Future Work

Hardware implementation and real-time validation of the converter.

Integration of closed-loop CC–CV control for enhanced charging performance.

Testing for scalability and robustness in practical EV charging systems.

🧑‍🏫 Supervision

Guide: Prof. Monalisa Pattnaik
Department of Electrical Engineering, NIT Rourkela
