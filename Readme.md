# Logic Gates in Verilog HDL

## Overview

This project implements the fundamental digital logic gates using **Verilog HDL**. It demonstrates the use of continuous assignments (`assign`) to model combinational logic and serves as a beginner-friendly reference for learning digital design.

The design is synthesizable and verified using **Xilinx Vivado**.

---

## Features

- AND Gate
- OR Gate
- XOR Gate
- NAND Gate
- NOR Gate
- Synthesizable combinational logic
- Functional simulation and RTL verification

---

## Module Description

### Module Name

`logicgates`

### Inputs

| Signal | Width | Description |
|--------|-------|-------------|
| A | 1-bit | First input |
| B | 1-bit | Second input |

### Outputs

| Signal | Width | Description |
|--------|-------|-------------|
| AND_OUT | 1-bit | Logical AND of A and B |
| OR_OUT | 1-bit | Logical OR of A and B |
| XOR_OUT | 1-bit | Logical XOR of A and B |
| NAND_OUT | 1-bit | Logical NAND of A and B |
| NOR_OUT | 1-bit | Logical NOR of A and B |

---

## Logic Equations

| Output | Expression |
|---------|------------|
| AND_OUT | `A & B` |
| OR_OUT | `A \| B` |
| XOR_OUT | `A ^ B` |
| NAND_OUT | `~(A & B)` |
| NOR_OUT | `~(A \| B)` |

---

## Truth Table

| A | B | AND | OR | XOR | NAND | NOR |
|---|---|-----|----|-----|------|-----|
| 0 | 0 | 0 | 0 | 0 | 1 | 1 |
| 0 | 1 | 0 | 1 | 1 | 1 | 0 |
| 1 | 0 | 0 | 1 | 1 | 1 | 0 |
| 1 | 1 | 1 | 1 | 0 | 0 | 0 |

---

## Project Structure

```
Logic-Gates/
│── logicgates.v
│── logicgates_tb.v
│── README.md
│── code.png
│── rtl_schematic.png
│── simulation_waveform.png
│── testbench.png
```

---

## Verilog Source Code

![Verilog Code](code.png)

---

## Testbench

![Testbench](testbench.png)

---

## RTL Schematic

![RTL Schematic](rtl_schematic.png)

---

## Simulation Waveform

![Simulation Waveform](simulation_waveform.png)

---

## Tools Used

- Verilog HDL
- Xilinx Vivado
- Vivado Simulator

---

## Applications

- Digital Logic Design
- FPGA Development
- VLSI Design
- ASIC Design
- Educational Projects

---

## Learning Outcomes

This project demonstrates:

- Verilog module creation
- Continuous assignments (`assign`)
- Combinational logic implementation
- RTL synthesis
- Functional simulation and verification

---

## Future Enhancements

- Add NOT gate
- Add XNOR gate
- Add Buffer gate
- Develop a self-checking testbench
- Extend the design using SystemVerilog

---

## Author

**Karthikeya Logitla**

Electronics and Communication Engineering (ECE)

Aspiring **VLSI Design & Verification Engineer**
