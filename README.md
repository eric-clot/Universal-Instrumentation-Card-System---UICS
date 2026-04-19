# **Universal Instrumentation Card System (UICS)**

Welcome to the **Universal Instrumentation Card System (UICS)** project. UICS aims to develop a **fully modular instrumentation system**, designed to be accessible to **everyone**, whether you're a **hobbyist, student, educator, research institution, or industry professional**.

---

## **Inspiration & Concept**
Inspired by modular systems like **NIM, TM 500, SIM, Eurocard and others**, UICS adopts the **proven idea of modularity**: each module performs a specific function (e.g., **DMM, lock-in amplifier, power supplies, controllers**) while sharing a **common connector pinout** and **backplane motherboard type**.

To **reduce costs**, UICS uses **PCI connectors on the motherboard** and **edge connectors on each module**, instead of traditional Eurocard connectors.

---

## **Standardization & Guidelines**
- A **connector pinout specification** will be published soon to standardize **power supplies, signals, and controls** across all modules.
- A **standardized nomenclature** will also be released shortly.

This repository will focus on:
- Project organization
- Module **definitions and guidelines** (size, pinout, enclosures, connectors)

---

## **Planned Modules (Non-Exhaustive List)**
Here’s a list of modules we plan to design:

### **Power & Control**
- Internal power supplies
- Control systems (RP2040, STM32)
- Screen interface
- USB hub (Computer Control Unit, CCU)
- Battery module (for autonomous operations)

### **Measurement & Amplification**
- Digital Multimeter (DMM)
- Transimpedance amplifier (for tuning forks)
- Lock-in amplifier
- Differential amplifier
- Low-noise current controller
- Low-frequency (LF) amplifier
- High-frequency (HF) amplifier
- High-voltage (HV) amplifier

### **Signal Generation & Acquisition**
- Voltage/current sources
- Data Acquisition (DAQ)
- Sine wave generator
- Arbitrary Waveform Generator (AWG)
- Active load
- Pulse counter
- Frequency meter (Frequencimeter)

### **Optics & Photonics**
- Laser source
- Photodiode 
- Avalanche photodiode (APD)
- Interferometer

### **Sensors & Specialized Modules**
- Magnetic sensor (probe type)
- Piezo controller (open/closed loop)
- Microwave generator
- Matrix switcher
- Spectrometer
- Semiconductor tester

### **Communication & Interfaces**
- Ethernet control unit
- GPIB interface
- RS232 interface
- Interrack link

---
**And many more to come!**
