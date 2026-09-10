# KineticStep: Kinetic Harvesting Floor Tile System

A reference repository for the Smart India Hackathon submission, presenting a piezoelectric-free kinetic energy harvesting floor tile mechanism utilizing a split-shaft planetary transmission and stepper motor generator.

---

## 1. Project Information

- **Project Title:** KineticStep – Kinetic Harvesting Floor Tile System
- **PS ID:** [26217]
- **PS Title:** [Student Innovation-Innovative ideas that help manage and generate renewable /sustainable sources more efficiently]
- **Category:** Hardware
- **Theme:** Renewable / Sustainable Energy

---

## 2. Problem Statement

Student Innovation-Innovative ideas that help manage and generate renewable /sustainable sources more efficiently
---

## 3. Proposed Solution

KineticStep is a piezoelectric-free energy harvesting floor tile that converts the vertical linear displacement of footsteps into rotational torque using a central rack-and-pinion assembly. This motion is accelerated through a two-stage split-shaft planetary gearbox (approximate 1:25 ratio) to drive a low-RPM NEMA 23 stepper motor generator. The resulting two-phase AC power is rectified and managed via an MPPT charge controller to charge a LiFePO4 battery storage bank safely.

---

## 4. Key Features

- **Piezoelectric-Free Transduction:** Replaces fragile crystals with a rugged mechanical transmission for high load capacity.
- **Constrained Vertical Stroke:** Restricted to 15 mm – 20 mm via elastomeric stoppers to prevent gear bottoming out.
- **High-Ratio Speed Multiplication:** Dual-stage split-shaft planetary gearbox (~1:25 ratio) stepping up low-speed human steps.
- **Mechanical Shock Isolation:** Flexible jaw coupling (Model D20L25) acts as a mechanical fuse, dampening impact loads and protecting motor bearings.
- **Kinematic Stability:** Triangular Aluminum 6061 top plate supported by three 8 mm casehardened steel guide shafts, linear bearings, and return springs.
- **Intelligent Energy Management:** Custom rectification paired with MPPT charge control and Smart BMS protection for LiFePO4 cells.

---

## 5. Technology Stack

- **Mechanical Chassis:** CNC-machined Aluminum 6061 (base plate and triangular top plate)
- **Linear Motion & Kinematics:** 8 mm casehardened steel linear shafts, linear bearings, elastomeric hard stops, and high-cyclic fatigue return springs
- **Transmission:** Precision steel rack and pinion set, two-stage split-shaft planetary gearbox (1:25 ratio), D20L25 flexible jaw coupling
- **Electrical Generation:** High-torque NEMA 23 stepper motor (2-phase AC low-RPM generator)
- **Power Electronics & Storage:** Custom 2-phase AC-to-DC rectification PCB, MPPT charge controller, LiFePO4 battery pack with Smart BMS
- **Prototyping & CAD:** Nylon/Carbon Fiber FDM filaments, Tough SLA Resin, Fusion 360 / SolidWorks

---

## 6. Architecture

See [docs/architecture.md](docs/architecture.md).

```text
[ Pedestrian Footstep Downforce ]
                 │
                 ▼
[ Triangular Top Plate & 3-Point Guide Assembly ]
                 │
                 ▼
[ Central Piston Head & Precision Linear Rack ]
                 │
                 ▼
[ Pinion Gear (Linear-to-Rotary Conversion) ]
                 │
                 ▼
[ Two-Stage Planetary Gearbox (1:25 Speed Multiplier) ]
                 │
                 ▼
[ Flexible Jaw Coupling (D20L25 - Shock Absorption) ]
                 │
                 ▼
[ NEMA 23 Stepper Motor (2-Phase AC Generation) ]
                 │
                 ▼
[ Custom Rectification & MPPT Power Management PCB ]
                 │
                 ▼
[ LiFePO4 Battery Storage & Telemetry ]
