
# 🧠 Design and Simulation of a 4-Bit Processor

## 📌 Project Description
This project implements a **simple 4-bit processor** using **Verilog HDL**.  
The processor is designed with a **custom instruction set** and demonstrates the core concepts of CPU operation such as instruction fetch, decode, execute, and write-back.

The design includes fundamental CPU components like **ALU, Register File, Control Unit, Program Counter, and Instruction Memory**.  
Simulation is performed using **ModelSim / Vivado**, and functionality is verified through waveform analysis.

---

## 🎯 Objectives
- Design a basic 4-bit CPU architecture
- Implement a custom instruction set
- Develop core processor modules using Verilog
- Simulate and verify CPU operations using waveform tools
- Understand processor-level data flow and control logic

---

## 🏗 Processor Architecture
The processor consists of the following blocks:

- **ALU (Arithmetic Logic Unit)**  
- **Register File (4 × 4-bit registers)**  
- **Control Unit**  
- **Instruction Memory**  
- **Program Counter (PC)**  

---

## 🧾 Instruction Set Architecture (ISA)

### Instruction Format (8-bit)

### Supported Instructions

| Opcode | Instruction | Operation |
|------|------------|-----------|
| 00 | ADD | Rd = Rd + Rs |
| 01 | SUB | Rd = Rd - Rs |
| 10 | AND | Rd = Rd & Rs |
| 11 | OR  | Rd = Rd \| Rs |

---
## 🧪 Simulation & Verification
- Simulated using ModelSim / Vivado Simulator
- Verified instruction execution and register updates
- Waveforms confirm correct ALU operations and data flow

  ---

## 🛠 Tools & Technologies

- HDL: Verilog
- Simulation: ModelSim

  ---
## 🚀 Applications

- Educational CPU design project

- FPGA-based learning system

- Understanding processor architecture

- Mini-project for academics and interviews

---
