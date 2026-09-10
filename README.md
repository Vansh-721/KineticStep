# KineticStep
# Kinetic Harvesting Floor Tile System

> **A piezoelectric-free kinetic energy harvesting floor tile mechanism utilizing a split-shaft planetary transmission and stepper motor generator.**

---

## Project Overview
The Kinetic Harvesting Floor Tile System is a renewable energy generation solution designed to convert the vertical linear motion of human footsteps into usable electrical energy. By replacing conventional piezoelectric elements with a robust mechanical rack-and-pinion assembly, a high-ratio two-stage planetary gearbox, and a low-RPM generator, the tile maximizes power generation efficiency and physical durability under continuous footfall loads.

* **Patent Status:** Provisional Patent Filed (Application No: `202611007986`)
* **Development Stage:** Early Prototyping & IP Protection
* **Maturity Level:** Technology Readiness Level 4 (TRL 4 - Laboratory Validation)

---

## Core Technical Specifications

| Subsystem / Parameter | Specification | Details |
| :--- | :--- | :--- |
| **Linear Stroke Range** | 15 mm – 20 mm | Mechanically limited by elastomeric stoppers on guide rods to prevent hard bottoming out. |
| **Transmission Ratio** | ~1:25 Speed Multiplication | Two-stage split-shaft planetary gear system linked by an 8 mm intermediate shaft. |
| **Generator Unit** | NEMA 23 Stepper Motor | Low-RPM generator producing 2-phase AC output. |
| **Mechanical Fuse** | Flexible Jaw Coupling (Model D20L25) | Absorbs minor shaft misalignments and footfall impact shock to protect motor bearings. |
| **Linear Guide System** | 3x Guide Rod Assemblies | 8 mm casehardened steel linear shafts with linear bearings in a triangular configuration. |
| **Return Mechanism** | Concentric Compression Springs | High-cyclic fatigue springs mounted around guide rods and linear bearings. |
| **Energy Management** | Custom Rectification + MPPT BMS | Converts 2-phase AC to DC; stores power in a LiFePO4 battery pack. |
| **Chassis / Top Plate** | CNC-machined Aluminum 6061 | Triangular top plate designed for industrial load distribution. |

---

## Working Principle & Energy Flow

1. **Downforce Application:** A pedestrian steps on the triangular top plate, driving the central piston head downward.
2. **Linear-to-Rotary Conversion:** The piston rod drives a precision rack and pinion gear through a constrained 15–20 mm vertical stroke.
3. **Speed Multiplication:** The pinion drives a two-stage split-shaft planetary gearbox (approximate 1:25 ratio), stepping up low-speed human input into high-RPM rotational torque.
4. **Mechanical Cushioning:** Rotational torque travels through a D20L25 flexible jaw coupling to absorb high-impact load spikes.
5. **Power Generation:** A high-torque NEMA 23 stepper motor acts as an AC generator, producing 2-phase power.
6. **Rectification & Storage:** The AC output is rectified to DC via custom circuitry and managed through an MPPT charging module into a LiFePO4 battery bank.

---

## List Of Components 

### Mechanical Systems
* **Chassis:** CNC-machined Aluminum 6061 base and triangular top plate.
* **Linear Motion:** 8 mm casehardened steel shafts, linear bearings, and elastomeric hard stoppers.
* **Gearing:** Precision steel rack & pinion set, two-stage planetary gearbox (1:25 ratio).
* **Return Mechanism:** Chrome silicon fatigue springs.
* **Rapid Prototyping (Validation):** Nylon/Carbon Fiber filament (wear-resistant gears), High-Precision Tough Resin (SLA tooth verification), and PLA/PETG drafting filaments.

### Electrical & Power Systems
* **Generation:** NEMA 23 High-Torque Stepper Motor.
* **Coupling:** Flexible jaw coupling (Model D20L25).
* **Power Electronics:** Custom rectification PCB, MPPT charge controllers.
* **Storage:** LiFePO4 battery pack with integrated Smart BMS.

---

## Team Members
* **Devyani Verma**
* **Deep Maurya**
* **Vansh Gupta**
* **Avneesh**
* **Garima**
* **Rudra**

---
