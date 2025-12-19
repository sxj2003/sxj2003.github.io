---
layout: project
type: project
image: images/mobile-arm.png
title: ROS-Based Mobile Manipulator for Sorting
permalink: projects/mobile-arm
# All dates must be YYYY-MM-DD format!
date: 2024-05-29
labels:
  - ROS
  - SLAM
  - Kinematics
  - Arduino
summary: A mobile robot system combining a 6-DOF arm and a mobile base for autonomous indoor waste collection and sorting.
---
color: olive
---


**Project Goals and Architecture**

This project, developed for the "Mechatronic Control Technology" course, aimed to create an indoor waste-clearing robot capable of autonomous navigation, target identification, and automated sorting. The system utilizes a "mobile base + 6-DOF robotic arm" architecture. For the chassis, we used ROS (Robot Operating System) with SLAM algorithms for environmental mapping and path planning, enabling autonomous obstacle avoidance.

**Kinematics and Sensor Integration**

I was primarily responsible for the control of the 6-DOF robotic arm, where I established D-H coordinate models and derived the forward and inverse kinematics equations to solve joint angle and spatial coordinate transformations. We also integrated an Arduino board to read RGB frequency data from color sensors. By writing logic algorithms, the arm was able to distinguish between different colored blocks, effectively simulating the sorting of various types of waste. The final system demonstrated a smooth workflow from navigation to target grasping and classification.


<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%; margin: 20px 0;">
    <iframe src="//player.bilibili.com/player.html?bvid=BV1ZnqDBhEsR&page=1&high_quality=1&danmaku=0" 
            style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;" 
            scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> 
    </iframe>
</div>
