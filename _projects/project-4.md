---
layout: project
type: project
image: images/SurgeryRobot.png
title: Magnetic Surgery Robot System via Imitation Learning
permalink: projects/SurgeryRobot
# All dates must be YYYY-MM-DD format!
date: 2025-06-01
labels:
  - Surgical Robotics
  - IL
  - Pytorch
summary: Developed an intelligent control architecture for a magnetically driven surgical robot to assist in minimally invasive cardiovascular interventions (TAVI).
color: olive
---

<img src="/images/magnetrobotics.gif" alt="Magnetic Surgery Robot Demo" style="width: 100%; display: block; margin: 0 auto;">

**Clinical Background and System Objectives**

To address the risks associated with Transcatheter Aortic Valve Replacement (TAVI/TAVR), particularly for high-risk elderly patients, our team designed a magnetically driven surgery robot system. By utilizing external magnetic fields to manipulate internal guidewires remotely, the system aims to reduce the radiation exposure for doctors and lower the technical difficulty of navigating complex arterial paths. I was responsible for the modular control system architecture, algorithm implementation, and system validation.

**Algorithm Design and Training**

I implemented an intelligent control strategy based on Imitation Learning to handle the non-linear friction and deformation of guidewires within vessels. This involved building a deep neural network in PyTorch and training it on expert datasets collected from skilled operators. Through extensive hyperparameter tuning experiments comparing 9 different combinations of learning rates and batch sizes, I determined that a Learning Rate of 0.001 and a Batch Size of 32 provided the optimal convergence for the model.

**Verification and Performance Metrics**

The project achieved excellent quantitative results, with the imitation learning strategy yielding a Mean Squared Error (MSE) of 0.622 and a Mean Absolute Error (MAE) of 0.347 on the test set. Physical testing on an aortic model demonstrated that the robot could smoothly navigate different vascular curvatures and reach target valve positions autonomously. This validation confirms the feasibility of using "imitation learning + magnetic robotics" to assist or partially replace manual operations in minimally invasive surgeries.
