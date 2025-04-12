# Audio Amplifier Project


![Zewail University Logo]([https://github.com/user-attachments/assets/fdb333e4-2ffe-4f90-a460-0b892389427e])

**Electro-Optic Sensors Project**  
**Authors:** Mohammed Harraz - Amr Khaled  
**Mentor:** Dr. Nehad Moustafa  
**Institution:** Zewail University, Egypt  

---

## 📋 Project Overview

This project focuses on designing and building a **three-stage transistor-based audio amplifier**.  
The goal is to amplify an input audio signal with a stable **voltage gain (Av) of 4.5**, and allow dynamic control of the gain.  
The design emphasizes low distortion, reliable PCB implementation, and real-world validation through measurements.

---

## 🛠️ Project Structure

### 1. Abstract
A brief overview of the design objectives:  
- Amplify audio signals with Av ≈ 4.5  
- Dynamic gain control  
- Operate at 12V DC supply  
- Ensure circuit stability and efficiency  

### 2. Introduction
Importance of audio amplifiers and key design aspects such as:  
- Proper component selection  
- Circuit modifications for gain control  
- Testing via simulation and practical measurements  

### 3. Circuit Design

#### Hand Analysis
- Calculated resistor values (R1, R2, RC) using circuit theory.
- Thevenin equivalent model used for biasing calculations.

#### LT-Spice Circuit Simulation
- Simulation of the designed amplifier circuit to verify theoretical gain and performance.

![LT-Spice Simulation](insert-simulation-image-link-here)

### 4. PCB Design

#### PCB Components
- 3 Transistors: 2SC1815 and 2N3904
- Resistors and capacitors carefully selected based on design
- Output: 600Ω speaker

#### Etching Process
- PCB fabricated by transferring design, etching copper, and soldering components.

![PCB Layout](insert-pcb-layout-image-link-here)
![Final PCB](insert-final-pcb-image-link-here)

---

## 📈 Results

| Parameter           | Theoretical | Simulated | Measured |
|---------------------|-------------|-----------|----------|
| Voltage Gain (Av)    | 4.5         | 4.48      | 4.42     |
| Output Voltage (Vo)  | 3.479 V     | N/A       | 4.17 V   |

- **Signal Quality:** Minimal distortion, good frequency response (20 Hz – 20 kHz).  
- **PCB Performance:** Stable, compact design with excellent thermal performance.

---

## ✅ Conclusion

The designed amplifier successfully achieved the desired gain and output voltage.  
The PCB implementation was effective in transferring simulated results into real-world measurements.  
This project demonstrates a strong link between theoretical design, simulation, and practical execution.

---

## 📂 Contents

- Hand Calculations
- LT-Spice Simulations
- PCB Layout and Fabrication
- Experimental Results
- Final Analysis and Conclusions

---

## 📸 Gallery

> Add your project images below by uploading them to GitHub and inserting links.

- LT-Spice Circuit Simulation  
- PCB Layout and Etching  
- Final Assembled PCB  
- Test Results  

---

## 📝 License

This project is part of academic coursework at Zewail University.  
© 2025 Mohammed Harraz, Amr Khaled. All rights reserved.
