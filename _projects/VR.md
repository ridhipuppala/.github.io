---
layout: project
date: 30 Nov 2018
title: Stereo-vision based position tracking of mobile VR headset
caption: Course Project
description: >
 Virtual Reality Engineering (Course) and Prof. Manivannan M. (Guide)
image: /assets/img/project/vr.png
screenshot:
 path: /assets/img/project/vr.png
 srcset:
 1920w: /assets/img/project/vr.png
 960w: /assets/img/project/vr.png
 480w: /assets/img/project/vr.png
coupro: true
---

This project was done for the course AM5011 - Virtual Reality Engineering. The objective of this project was to create an efficient and cost-effective position tracking system for smartphone virtual reality, to enhance user experience such that it can work in combination with head orientation tracking and virtual environment generation software. In other words, aim was to develop a compact and modular setup for positional tracking in constrained indoor locations. I incorporated disparity calculations on CNN based human body tracking from two USB cameras for 3D shoulder pose estimation, which is then used to compute 3D real-time position of smartphone VR headset. Openpose convolutional neural network (CNN) developed by CMU was used in the work and Unity3D engine was used to render and visualize the VR simulations.

The following video illustrates the results of the work briefly.

<div>
<iframe width="900" height="506" src="https://www.youtube.com/embed/z2FFakWWeG8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

You can read more about the project in this [report](/assets/VR_report.pdf) and this [presentation](/assets/VR_ppt.pdf). Code is available [here](https://github.com/ridhipuppala/VR_project).

## Assignment

As a part of course assignment, I developed a Sensor fusion smartphone application to extract accurate roll, pitch and yaw estimates from accelerometre, Gyroscope and magnetometer sensor measurements. Application was developed using Android studio (Java) to toggle between different methods of smartphone orientation estimation methods, namely, Kalman filter, Complimentary filter, Gyro (independent) and Accelerometre (independent) modes. Code is available [here](https://github.com/ridhipuppala/FusionR_androidapp).

![fusionapp.png](fusionapp.png)
