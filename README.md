# 🏗️ Pick & Place XYZ System
**PLC: CODESYS V3.5 | Simulation: Factory I/O**

A high-precision industrial robotic solution for 3-axis item handling. This project focuses on coordinate-based motion control and synchronized pick-and-place operations.

## ⚡ Key Highlights
* **3-Axis Motion Control:** Precise positioning using **X, Y, and Z** actuators for warehouse organization.
* **Vacuum Gripper Logic:** Integrated suction pad control with sensor feedback to ensure successful item pick-up.
* **Smart Palletizing:** Automated logic to detect incoming items and place them in pre-defined grid coordinates.
* **Optimized Pathfinding:** Sequential state machine logic to minimize travel time between the source and destination.
* **Safety & Interlocks:** Full integration of emergency stops and limit switches to prevent mechanical collisions.

## 🏗️ Technical Setup
* **Logic:** **Structured Text (ST)** for the XYZ coordinate state machine + **Ladder Diagram (LD)** for hardware I/O and sensor interfacing.
* **State Management:** Advanced execution flow using **ENUMs** and **CASE OF** to manage "Pick", "Travel", and "Place" cycles.
* **Coordinate Mapping:** Implementation of arrays or constants to define drop-off points in the 3D space.
* **Architecture:** Modular Function Blocks (FBs) designed for reusable motion profiles and Global Variable Lists (GVLs) for system-wide signals.

## 📸 In Action
![System Demo](Media/Pick_Place_XYZ_Factory_IO_Codesys.gif)
