---
layout: project
type: project
image: images/PedestalDesign1.png
title: Dual-DOF Parallel Antenna Pedestal Design
permalink: projects/PedestalDesign
# All dates must be YYYY-MM-DD format!
date: 2025-01-15
labels:
  - Parallel Mechanisms
  - ANSYS
  - Simulink
  - Solidworks
  - UG
summary: A high-rigidity parallel antenna turntable designed for high-speed train radar tracking, verified through fluid-structure interaction and joint simulation.
color: olive
---

<img src="/images/PedestalDesign3.png" alt=" LightweightDesign" style="width: 100%; display: block; margin: 0 auto;">

<img src="/images/PedestalDesign4.png" alt=" LightweightDesign" style="width: 100%; display: block; margin: 0 auto;">

**Design Motivation and Structure**

This project aimed to design a dual-degree-of-freedom parallel antenna pedestal for high-speed trains to ensure precise tracking of dynamic targets in complex environments. Compared to traditional serial structures, this parallel design significantly improves rigidity and load-bearing capacity while maintaining a lightweight profile to withstand wind loads. The mechanical structure includes a central column, hook-joint parallel links, and a circular rail gear system, allowing for ±360° azimuth and 0~52° pitch motion.

**Simulation and Control Implementation**

We utilized ANSYS and Fluent for fluid-structure interaction analysis, verifying structural safety under extreme wind speeds of 128 km/h. My core contribution was the development of a joint simulation platform using UG/NX and Simulink. I applied a PID algorithm for closed-loop control to manage the complex non-linear control challenges of parallel mechanisms. The results showed that the steady-state error for both pitch and azimuth motion converged to 0.06°, which is significantly better than the 0.3° design requirement.

