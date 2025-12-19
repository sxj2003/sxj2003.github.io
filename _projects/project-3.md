---
layout: project
type: project
image: images/writing-robot.jpg
title: Arduino-Based CNC Writing Robot
permalink: projects/writing-robot
# All dates must be YYYY-MM-DD format!
date: 2022-10-30
labels:
  - Arduino
  - CNC
  - Mechatronics
  - G-Gode
summary: A high-precision automated drawing robot developed as a final project for 'Introduction to Engineering'.
color: olive
---



**Design Philosophy and Components**

As a final project for the "Introduction to Engineering" course, our team designed and manufactured a writing robot to explore the practical applications of mechatronic systems. The system is built around an Arduino UNO R3, utilizing a CNC Shield V3 to drive 42-stepper motors for precise XY-axis positioning. For the Z-axis, an MG90s servo controls the lifting and lowering of the pen. On the software side, we used Inkscape to convert vector graphics into G-code, which was then sent to the hardware via the Grbl Controller host computer.

**Implementation and Outcomes**

Despite the challenges of remote collaboration during the pandemic lockdown, our team successfully completed everything from circuit connection and code debugging to final assembly. We also implemented custom code to enable a passive buzzer for audio operation prompts. The final product demonstrated high-precision replication, capable of writing neat slogans and drawing highly detailed line art, fulfilling all expected engineering objectives.

<video width="100%" controls>
  <source src="/images/writing-robot-video.mp4" type="video/mp4">
  您的浏览器不支持 HTML5 视频。
</video>

<video width="100%" controls>
  <source src="/images/writing-robot-video2.mp4" type="video/mp4">
  您的浏览器不支持 HTML5 视频。
</video>