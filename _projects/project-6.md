---
layout: project
type: project
image: images/robotics.png
title: ABB IRB 1200 Robot Simulation & Workspace Optimization
permalink: projects/robotics
# All dates must be YYYY-MM-DD format!
date: 2024-06-04
labels:
  - Robotics
  - MATLAB
  - Monte Carlo
summary: Full-cycle design of a 6-DOF collaborative robot, featuring an improved Monte Carlo method for efficient workspace analysis.
color: olive
---

<img src="/images/robotics1.png" alt="roboticsSimulation" style="width: 100%; display: block; margin: 0 auto;">

<img src="/images/robotics2.png" alt="roboticsSimulation" style="width: 100%; display: block; margin: 0 auto;">

**Modeling and Theoretical Derivation**

For the "Robotics" course, our team designed a 6-DOF collaborative robot based on the industrial ABB IRB 1200 model. We managed the entire process from mechanical modeling in SolidWorks to mathematical derivation and motion control simulation. We constructed MDH parameter tables, derived kinematics equations, and solved dynamics problems using the Lagrangian equation. A PID controller was designed in MATLAB/Simulink to achieve velocity and position loop control while suppressing gravity interference.

**Workspace Analysis Innovation**

I was specifically responsible for workspace analysis, where I implemented an improved Monte Carlo method to address the efficiency issues and blurry boundaries of traditional approaches. By employing a "seed space generation and dynamic boundary expansion" strategy, I optimized the distribution of point clouds. This improved algorithm required only 4.22% of the sampling points used by traditional methods to reach equivalent volume calculation accuracy. The final project successfully demonstratsed complex tasks, including circular trajectory drawing and aerial object interception.


