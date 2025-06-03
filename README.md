# Synchronous_Down_counter_9_to_10
HDL code,K-map,Block Diagram

# 💻 Hack CPU & 4-Bit Synchronous Down Counter

This project is developed as part of the **Elements of Computing** course at Amrita School of Artificial Intelligence. It is divided into two main parts:

1. **Part A** – Design and implementation of a 16-bit Hack CPU architecture using HDL
2. **Part B** – Design and simulation of a 4-bit synchronous down counter (from 9 to 0)

---

## 👩‍💻 Team Members
- **Varshitha Thilak Kumar** – varshitha.9a2019@gmail.com
- **Siri Sanjana S** – sirisanjana.singareddy@gmail.com
- **Shreya Arun** – shreyaarun005@gmail.com 
> Department: CEN, Amrita School of Artificial Intelligence, Coimbatore Campus

---

## 🧠 Part A: Hack CPU

The Hack platform is a 16-bit von Neumann architecture designed to execute low-level machine code.

### 🔧 Components Implemented

- **ALU**: 16-bit Adder with NOT, AND, OR, Multiplexors
- **Registers**:
  - Data Register (D)
  - Address Register (A)
  - Program Counter (PC)
- **Memory**:
  - ROM for instructions
  - RAM for data
- **Screen and Keyboard**: Built-in chips for I/O

### 🛠 HDL Chips Implemented

- `ALU.hdl`
- `DRegister.hdl`
- `ARegister.hdl`
- `ProgramCounter.hdl`
- `Memory.hdl`
- `CPU.hdl`

### 💡 Summary

- CPU architecture built using HDL based on nand2tetris platform
- Program flow controlled via PC and decoded through C-instructions
- Instruction types: A-instruction, C-instruction
- Designed and simulated using Hack HDL Simulator

---

## 🔁 Part B: 4-Bit Synchronous Down Counter (9 to 0)

### 🧩 Digital Logic Design

- Built using **T Flip-Flops** and **Combinational Logic**
- State transitions: 1001 (9) → 0000 (0)
- Counter decrements on every clock pulse
- State changes are synchronous (all flip-flops triggered simultaneously)

### 🧮 Design Tools

- Truth Table
- K-Map simplification
- State Diagram
- HDL Simulation of T-FFs and counter logic

### 💡 Summary

- Designed a synchronous down counter using logic gates and flip-flops
- HDL code simulates correct decrement from 9 to 0
- Reinforced understanding of digital logic and sequential design

---

## 📂 File Structure

├── partA_hack_cpu/
│ ├── ALU.hdl
│ ├── CPU.hdl
│ ├── Memory.hdl
│ ├── DRegister.hdl
│ └── ARegister.hdl
├── partB_down_counter/
│ ├── DownCounter.hdl
│ ├── TFlipFlop.hdl
├── README.md
└── EOC_FINAL.pdf


---

## ✅ Conclusion

This project demonstrates the design, simulation, and implementation of a 16-bit CPU along with a sequential logic counter. It reinforces fundamental computing concepts by bridging software logic with hardware simulation using HDL.


