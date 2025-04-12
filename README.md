# Audio Amplifier Project

**Authors:** Mohammed Harraz & Amr Khaled  
**Mentor:** Dr. Nehad Moustafa  
**Zewail University, Egypt**

---

## Project Overview

This project focuses on designing and implementing a three-stage transistor-based audio amplifier.  
The objective was to achieve a voltage gain (Av) of approximately 4.5, while maintaining stable operation and providing dynamic gain control.

The project includes:
- Theoretical circuit analysis
- LT-Spice simulations
- PCB design and fabrication
- Real-world testing and evaluation

---

## Tools and Components

- **Transistors:** 2SC1815, 2N3904
- **Resistors:**
  - R1 = 6.32 kΩ
  - R2 = 11.96 kΩ
  - RC = 2.7 kΩ
- **Capacitors:**
  - C1 = 0.1 µF
  - C2 = 47 µF
  - C3 = 220 µF
- **Supply Voltage:** 12V
- **Output Load:** 600 Ω speaker
- **Software:** LT-Spice (for simulation)

---

## Project Details

### 1. Hand Analysis
Manual calculations were performed to determine resistor values (R1, R2, RC) based on the required gain and supply voltage.

### 2. LT-Spice Circuit Simulation
The circuit was simulated using LT-Spice to verify gain, signal quality, and stability.

![LT-Spice Circuit Design](images/Ltspice.png)

### 3. PCB Design and Fabrication
The PCB was designed, etched, and soldered following standard fabrication processes.

![PCB Layout](images/pcb_layout.png)

### 4. Results

| Metric                | Theoretical | Simulated | Measured  |
|-----------------------|-------------|-----------|-----------|
| Voltage Gain (Av)     | 4.5         | 4.48      | 4.42      |
| Output Voltage (Vo)   | 3.479V      | —         | 4.17V     |

- **Signal Quality:** Minimal distortion observed within the full audio frequency range (20 Hz – 20 kHz).
- **PCB Performance:** Compact, thermally efficient, and stable.

---

## Conclusion

The audio amplifier project successfully achieved the target specifications:
- Voltage gain close to the desired value
- Reliable and stable circuit operation
- Effective translation from theoretical design to practical implementation

The PCB was validated through real-world testing, confirming the accuracy of simulations and hand analysis.

---

## Project Images

| Hand Analysis | PCB Fabrication | Final Circuit |
|:-------------:|:---------------:|:-------------:|
| ![Hand Analysis](images/hand_analysis.png) | ![Etching Process](images/etching_process.png) | ![Final Amplifier](images/final_circuit.png) |

---

## License

This project was developed for academic purposes at Zewail University.  
It may be reused and modified for educational or personal projects.
