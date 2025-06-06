# 🔧 RISC-V Single-Cycle Datapath (RV32I) – Logisim Implementation

This project implements a **single-cycle datapath** for the **RV32I subset** of the **RISC-V Instruction Set Architecture** using **Logisim**. The design covers the complete execution flow of RISC-V instructions and includes essential datapath components modeled visually for learning purpose.

---

## 🧠 Project Overview

- 📘 **Architecture**: Based on the RV32I base instruction set (32-bit, integer-only).
- 🛠️ **Platform**: Designed using [Logisim](http://www.cburch.com/logisim/), a digital logic simulator.
- 🧩 **Design Philosophy**: Clean, modular structure for clarity and extensibility.

---

## 📦 Components

The datapath includes:

- **Program Counter (PC)**
- **Instruction Memory**
- **Control Unit**
- **Register File**
- **ALU (Arithmetic Logic Unit)**
- **Immediate Generator**
- **Data Memory**
- **Branch Decision Logic**
- **Multiplexers and Sign Extenders**

Each component is implemented as a Logisim subcircuit to maintain modularity.

---

## 🧪 Features

- Executes **R-type**, **I-type**, **S-type**, **B-type**, **U-type**, and **J-type** instructions from the RV32I set.
- Fully functional control unit to manage datapath control signals.
- Immediate generation logic to support multiple instruction formats.
- Visual simulation and step-by-step instruction execution using Logisim.

---

## 📁 Repository Contents

- `RISC-V_Datapath.circ` – Main Logisim circuit file containing the full single-cycle datapath.
- `README.md` – Project documentation (you’re here).
---

## 🚀 How to Use

1. Open `RISC-V_Datapath.circ` in Logisim.
2. Load or manually enter an instruction in the instruction memory.
3. Set the clock to manual for step-by-step debugging, or automatic for continuous execution.
4. Observe the signal flow, register values, and memory updates.

---

## 📚 Educational Value

This project is ideal for:

- Learning the **fundamentals of CPU architecture**.
- Visualizing **how RISC-V instructions are processed** in hardware.
- Experimenting with extensions and pipelining concepts.


