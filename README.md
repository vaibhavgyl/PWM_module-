# FPGA PWM Generator (Verilog, ModelSim, Vivado)

This project implements a **Pulse Width Modulation (PWM) controller** using **Verilog HDL** and verifies its functionality through **RTL simulation**.  
It demonstrates key concepts in **digital system design**, **timing analysis**, and **hardware prototyping** on **FPGA platforms**.

---

## 🔧 Features
- Parameterized **PWM generator** with adjustable duty cycle  
- Fully **synthesizable RTL design** for FPGA (tested on Xilinx devices)  
- **Clock division** and **duty-cycle control logic** for flexible signal generation  
- **Testbench included** for functional verification using ModelSim or Vivado Simulator  
- Demonstrates **RTL design flow**, **functional verification**, and **timing closure**

---

## 🧩 Tools & Technologies
- **Languages:** Verilog HDL  
- **EDA Tools:** ModelSim / Vivado  
- **Hardware:** Xilinx Artix-7 (Basys3 / Nexys A7)  
- **Concepts:** SoC Design · FPGA Prototyping · RTL Verification · Timing Analysis · Low-Power Design

---

## 🚀 How to Run
### 1. Simulation
1. Open ModelSim or Vivado Simulator.  
2. Compile `pwm.v` and `pwm_tb.v`.  
3. Run simulation and observe waveform (`pwm_out` vs `duty`).  

```tcl
vlog pwm.v pwm_tb.v
vsim pwm_tb
run -all
