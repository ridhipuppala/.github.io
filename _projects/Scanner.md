---
layout: project
date: 30 Nov 2015
title: 3D Scanner (Elec Club, IIT Madras)
caption: Student led project
description: >
 Project for giving hands-on experience to basic controls and instrumentation
image: /assets/img/project/scanner.png
screenshot:
 path: /assets/img/project/scanner.png
 srcset:
 1920w: /assets/img/project/scanner.png
 960w: /assets/img/project/scanner.png
 480w: /assets/img/project/scanner.png
coupro: true

---

This project was my first hands on experience with robotics and electronics at the Electronics club of Centre for Innovation (CFI) IIT Madras. This exposed me to programming in *C++* and *Python*, Arduino programming, basics of embedded design and electronics, sensors, actuators, Computer Vision algorithms, scoket programming, prototyping and taught me several other practical skills and tools. Our team developed a cost-effective and portable 3D scanner with accuracy within permissible limits. It was developed as product for hobbyists. We conceptualized frugal scanning setup with elements like USB camera, laser & stepper motor based rotating platform. Morphological transformations & denoising algorithms were scripted using *OpenCV* *C++ * library to extract line laser pixels. OpenGL and Meshlab were used for post-processing, visualization and meshing of 3D point cloud. Fianlly, we developed a system that can scan an in less than two minutes and then a create a 3D mesh file which can be converted into an STL file for 3D printing. Code is available here.

You can read more about the project in this [report](/assets/3Dscanner_report.pdf). Code is available [here](https://github.com/ridhipuppala/3DScanner).
