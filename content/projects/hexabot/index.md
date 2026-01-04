---
title: "Hexapod Robot — Tripod Gait & IK"
summary: "Tripod gait inverse kinematics and simulation for a 6-legged robot with 3-DOF legs."
date: 2025-01-01
weight: 4
showHero: true
heroStyle: big
tags: ["Robotics", "Hexapod", "Inverse Kinematics", "ROS 2", "Simulation"]

links:
  - title: GitHub
    url: https://github.com/AaksharGarg/Hexapod
    icon: github

---

## Demo Video

{{< youtube bczUX5QVebA >}}

## Overview
Ongoing development of a **rectangular-base hexapod robot** equipped with **six 3-DOF legs**, focusing on
stable locomotion using a **tripod gait** and accurate **inverse kinematics (IK)** for planar terrain traversal.

The project emphasizes realistic simulation, modular control pipelines, and extensibility toward
autonomous navigation on uneven terrain.

## Key Contributions
- Designed and implemented **tripod gait inverse kinematics** for a rectangular-base hexapod.
- Developed kinematic models for **six independent 3-DOF robotic legs**.
- Built a full **GZ-Harmonic simulation** of the hexapod robot.
- Integrated a **trajectory control plugin** for smooth and synchronized leg motion.
- Validated gait stability and traversal performance on planar terrain in simulation.

## Simulation & Control
- Accurate URDF/XACRO modeling for multi-legged locomotion.
- Gait phase coordination to ensure static stability.
- Trajectory interpolation for continuous foot motion.

## Future Scope
- Integration of **ORB-SLAM** for localization and mapping.
- Development of **terrain-adaptive IK** using **OctoMap**.
- Integration with **MoveIt** for advanced motion planning.
- Extension from planar traversal to **uneven and unstructured terrain**.

## Tech Stack
- **Middleware & Simulation:** ROS 2, GZ-Harmonic  
- **Robotics:** Hexapod Inverse Kinematics, Gait Planning  
- **Motion & Planning:** Trajectory Control Plugins  
- **Programming:** Python, C++  
