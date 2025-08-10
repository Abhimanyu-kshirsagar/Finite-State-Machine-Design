# Finite-State-Machine-Design
 Designed a sequence detection circuit using both Moore and Mealy FSM, Design was implemented HDL Language Used: verilog

 # 🔄 Finite State Machine Sequence Detector (Moore & Mealy)

## 📌 Project Overview
This project implements **both Moore and Mealy finite state machines (FSMs)** in Verilog HDL to detect a specific binary sequence (`1011`).  
The aim was to compare Moore and Mealy designs in terms of timing, output behavior, and complexity.

---

## 🎯 Features
- Sequence: `1011`
- **Moore FSM**: Output depends only on the current state (stable but slightly delayed).
- **Mealy FSM**: Output depends on current state & input (faster but can be glitchy).
- Testbenches for both FSMs.
- Self-checking verification for multiple input patterns.

---

## 🛠 Tools & Technologies
- **Language:** Verilog HDL
- **Simulator:** Icarus Verilog / ModelSim
- **Waveform Viewer:** GTKWave

---

## 📂 Repository Structure

