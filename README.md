# Industrial Robotics: Trajectory Control & Tool Handling (RAPID)

## 🎯 Overview
This project demonstrates advanced motion control in **ABB RAPID** for precision handwriting tasks. It simulates the complete cycle of a robotic cell, including tool procurement and complex path planning.

## 🛠️ Technical Features
- **Motion Commands:** Implementation of `MoveJ` (air movements), `MoveL` (linear interpolation for drawing), and `MoveC` (circular interpolation for curves).
- **Coordinate Systems:** Usage of `tooldata` (tPencil) and `wobjdata` (wTable) for decoupled programming.
- **Modular Design:** Procedures organized by letters for scalable and readable code.

## 📊 Logic Flow
1. **Tool Acquisition:** Approaching the pencil case and synchronizing I/O for gripper control.
2. **Path Execution:** Dynamic calculation of offsets to draw the name "PABLO" with sub-millimeter precision.
3. **Safety Protocol:** Use of `RelTool` for safe approaches and retreats from the work surface.

## 💻 Simulation
*Developed and tested in RobotStudio 2025.*
