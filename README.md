# RISC-V Single Cycle Core

A simple RISC-V Single Cycle Processor designed using Verilog HDL.  
This project implements the basic datapath and control unit of a RISC-V processor capable of executing instructions in a single clock cycle.

---

## Features

- Single Cycle RISC-V Architecture
- Verilog HDL Implementation
- ALU Operations
- Register File
- Program Counter (PC)
- Instruction Memory
- Data Memory
- Control Unit
- Branch and Jump Support
- Simulation using GTKWave

---

## Supported Instructions

- R-Type Instructions
  - ADD
  - SUB
  - AND
  - OR
  - XOR

- I-Type Instructions
  - ADDI
  - LW

- S-Type Instructions
  - SW

- SB-Type Instructions
  - BEQ

- UJ-Type Instructions
  - JAL

---

## Architecture

Single Cycle Datapath includes:

- Program Counter
- Instruction Memory
- Register File
- ALU
- Data Memory
- Control Unit
- Immediate Generator
- Multiplexers

---

## Tools Used

- Verilog HDL
- Icarus Verilog
- GTKWave
- VS Code

---

## Folder Structure

/project
│
├── design.v
├── testbench.v
├── instruction_Mem.v
├── data_Mem.v
├── register_File.v
├── alu.v
├── control_Unit.v
├── dump.vcd
├── gtkwave.gtkw
└── README.md

---
##Output
<img width="1918" height="1023" alt="Screenshot 2026-05-12 222302" src="https://github.com/user-attachments/assets/63bcd950-37ef-4c62-9a56-5f30511ab977" />

## How to Run

### Compile

```bash
iverilog -o out design.v testbench.v
