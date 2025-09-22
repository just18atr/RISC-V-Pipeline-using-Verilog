
# RISC-V-I Design in Verilog

This project implements the **RISC-V Integer (RV32I) instruction set architecture** in **Verilog RTL**, covering core components such as instruction fetch, decode, execute, and memory access. The design follows a **von Neumann architecture** with unified instruction and data memory.

---

## 🔑 Features

* **Instruction Fetch & Memory Interface**

  * Program Counter (PC) driven instruction fetch with memory access logic.
* **Arbiter Module**

  * Manages instruction and data flow in a **von Neumann architecture**, ensuring correct memory arbitration.
* **Instruction Decode Unit**

  * Supports decoding of **R-type, I-type, S-type, B-type, and J-type** instructions.
* **Execute Module**

  * Handles **ALU operations, load/store, branch, and jump instructions** based on decoded opcodes.

---

## 🛠️ Technology & Tools

* **HDL**: Verilog
* **Architecture**: RV32I (Integer subset of RISC-V)
* **Tools**: (replace with yours: ModelSim / Icarus Verilog / Vivado / GTKWave)

---

## 📊 Results

* Successfully simulated instruction execution across all **RV32I base instruction types**.
* Verified correct **instruction fetch → decode → execute → memory → write-back** pipeline flow.
* Functional correctness confirmed using test programs.

---

## 📂 Repository Structure

```
├── /rtl             # Verilog RTL source files
├── /tb              # Testbenches for modules
├── /docs            # Documentation, block diagrams, instruction set notes
└── README.md        # Project description
```

---

## 🚀 Applications

* Educational RISC-V CPU design project
* Base framework for pipelined or superscalar extensions
* Integration into SoC or FPGA implementations

---

