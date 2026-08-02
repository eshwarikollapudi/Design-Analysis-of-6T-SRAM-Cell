# 💾 Design & Analysis of 6T SRAM Cell

A CMOS-based VLSI design project focused on the implementation and performance evaluation of a conventional **6-Transistor (6T) Static Random Access Memory (SRAM)** cell. The project explores the design, operation, and analysis of the SRAM cell using **Cadence Virtuoso** and **Spectre Simulator**, with emphasis on stability, read/write functionality, Static Noise Margin (SNM), and power-performance trade-offs.

---

# 📖 Overview

Static Random Access Memory (SRAM) is one of the most widely used memory technologies in modern digital systems due to its high speed, low latency, and reliable performance. This project presents the design and analysis of a conventional 6T SRAM cell implemented using CMOS technology.

The design process includes transistor sizing, schematic implementation, and simulation using industry-standard Electronic Design Automation (EDA) tools. The project evaluates the SRAM cell through DC and transient analyses to study its behavior during hold, read, and write operations. Voltage Transfer Characteristics (VTC) and Static Noise Margin (SNM) are analyzed to determine the stability and robustness of the memory cell. The study also highlights the design trade-offs between stability, speed, and power consumption, providing practical insights into SRAM design for modern VLSI applications.

---

# 🎯 Objectives

- Design a conventional 6T SRAM cell using CMOS technology.
- Analyze the architecture and operation of the SRAM cell.
- Perform DC and transient simulations using Cadence Virtuoso.
- Evaluate Static Noise Margin (SNM) using the butterfly curve.
- Study read, write, and hold operations.
- Understand the impact of transistor sizing on SRAM performance.

---

# ✨ Features

- 💾 6T SRAM Cell Design
- ⚡ CMOS Technology Implementation
- 📊 DC and Transient Analysis
- 🦋 Static Noise Margin (SNM) Evaluation
- 📈 Voltage Transfer Characteristics (VTC)
- ⚙️ Read, Write and Hold Operation Analysis
- 📉 Performance and Stability Evaluation
- 🖥️ Cadence Virtuoso & Spectre Simulation

---

# 🏗️ 6T SRAM Cell Architecture

```text
                 VDD
                  │
          ┌─────────────┐
          │ Cross-Coupled│
          │ CMOS Inverters│
          └─────────────┘
             │        │
             Q        QB
             │        │
          Access   Access
        Transistor Transistor
             │        │
            BL       BL̅
               │
              WL
```

---

# 🔄 Modes of Operation

### Hold Mode
The word line remains LOW, isolating the memory cell from the bitlines while the cross-coupled inverters retain the stored data.

### Read Operation
Both bitlines are precharged, and the word line is enabled. The stored data is sensed through the bitlines while maintaining cell stability.

### Write Operation
The desired data is applied to the bitlines, and enabling the word line updates the stored value inside the SRAM cell.

---

# 🛠️ Technologies Used

- Cadence Virtuoso
- Spectre Simulator
- CMOS Technology
- Electronic Design Automation (EDA)
- VLSI Design
- Analog & Mixed Signal Design

---

# 📂 Project Structure

```text
Design-Analysis-of-6T-SRAM-Cell/
│
├── README.md
├── Report.pdf
├── Schematic/
├── Simulation/
├── Results/
├── Images/
└── Documentation/
```

---

# ⚙️ Simulation Flow

1. Select CMOS technology.
2. Design the 6T SRAM schematic.
3. Perform transistor sizing.
4. Configure the simulation testbench.
5. Run DC Analysis.
6. Generate Voltage Transfer Characteristics (VTC).
7. Calculate Static Noise Margin (SNM).
8. Perform transient analysis.
9. Evaluate read, write, and hold operations.
10. Analyze stability and performance.

---

# 📊 Results

The project successfully demonstrates:

- Successful implementation of a conventional 6T SRAM cell.
- Stable data retention during hold operation.
- Correct read and write functionality.
- Voltage Transfer Characteristics (VTC) analysis.
- Static Noise Margin (SNM) evaluation using the butterfly curve.
- Performance analysis under different operating conditions.
- Understanding of the trade-offs between stability, speed, and power consumption.

---

# 🚀 Future Scope

- Low-power SRAM optimization
- High-density SRAM array design
- FinFET-based SRAM implementation
- Process variation analysis
- Low-voltage SRAM design
- Advanced memory architectures for AI and IoT applications

---

# 📸 Screenshots

Include screenshots of:

- 6T SRAM Schematic
- Cadence Virtuoso Design
- DC Analysis
- Voltage Transfer Characteristics (VTC)
- Butterfly Curve
- Static Noise Margin (SNM)
- Transient Analysis
- Read/Write Waveforms

---

# 👤 Author

**K. L. Eshwari**  
B.Tech, Electronics and Communication Engineering  
SRM University-AP

---

## 🎓 Project Guide

**Dr. Bharat Bhushan Upadhyay**

---

# 📄 License

This project is licensed under the **MIT License**.

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub. Your support is greatly appreciated!
