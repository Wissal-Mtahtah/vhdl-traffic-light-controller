# VHDL Traffic Light Controller – Finite State Machine

## 📌 Project Description
This project presents the design and simulation of a traffic light control
system using the VHDL hardware description language. The system controls
three traffic lights (red, green, and orange) at a road intersection and
operates according to a predefined timing sequence.

The project was developed as part of an embedded electronics module and
focuses on finite state machines (FSM), sequential logic, and digital system
simulation.

---

## 🎯 Objectives
The main goals of this project are to:
- Design a finite state machine for a traffic light system
- Implement the FSM using VHDL
- Simulate and validate the behavior using Vivado
- Understand timing, state transitions, and reset behavior

---

## 🧠 System Overview
The traffic light controller is based on a finite state machine with
three main states:

- **RED**: Red light active
- **GREEN**: Green light active
- **ORANGE**: Orange light active

The system is driven by a clock signal and includes a reset input to
force the system back to its initial state.

State transitions are controlled using an internal counter:
- RED → GREEN after 10 clock cycles
- GREEN → ORANGE after 10 clock cycles
- ORANGE → RED after 4 clock cycles

---

## 🔧 Technologies & Tools
- **VHDL** – Hardware description language
- **Vivado (Xilinx)** – Simulation and design environment
- **Finite State Machines (FSM)**
- **Testbench-based simulation**

---

## 🧪 Simulation
A VHDL testbench was developed to:
- Generate a clock signal
- Apply reset conditions
- Observe state transitions over time

Simulation results confirm that:
- Each traffic light activates for the correct duration
- State transitions occur at the expected clock cycles
- The reset correctly returns the system to the RED state

---

## 📄 Documentation
The full project report is available in the folder and includes:
- System description
- State graph
- VHDL architecture explanation
- Testbench structure
- Simulation results and analysis

---

## 📂 Source Code
The VHDL source files are not currently included in this repository.
They will be added in the future once recovered.

(The full code is partially shown and explained in the project report.)

---

## 👤 Author
**Wissal Mtahtah**  
Mechatronics Engineering Student  

Université Abdelmalek Essaâdi  
École Nationale des Sciences Appliquées de Tétouan  
Academic Year: 2024 / 2025

---

## 🎓 Academic Context
This project was developed as part of the *Embedded Electronics* module
to practice digital system design using VHDL and finite state machines.
