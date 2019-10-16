---
layout:       project
date:         25 July 2019
title:        Reactive navigation controller under minimal information access
caption:      Research Internship
description:  Research internship at A.R.M.S. Lab, Systems and Control Engineering IIT Bombay
image:        /assets/img/project/arms.jpg
screenshot:
  src:        /assets/img/project/arms.jpg
  srcset:
    1920w:    /assets/img/project/arms.jpg
    960w:     /assets/img/project/arms.jpg
    480w:     /assets/img/project/arms.jpg

featured:     true
#accent_color: '#ee682a'
#accent_image: /assets/img/sidebar-bg.jpg
---

In the summer of 2019, I worked as research intern at the Autonomous Robots and Multi-robot Systems ([A.R.M.S.](http://www.sc.iitb.ac.in/robotics/index.html)) Lab which is a part of the Systems and Control Engineering Department at IIT Bombay. Main objective of the work was to develop and test a reactive controller for globally convergent navigation in the presence of convex obstacles. This work was done in collaboration with Arun G.K. pursing PhD at ARMS Lab, and supervised by Prof. Leena Vachhani.

## My contribution

I formulated a planar global reactive navigation controller that just utilizes coarse bearing-only and 2D LIDAR measurements. The controller has been derived by fusing homing & boundary following controllers with novel exit condition that uses sign change information of bearing-only measurements. I have mathematically derived the exit conditions and controllers for static and moving targets using concepts of geometry, sliding mode control, nonlinear analysis and Lyapunov-like stabilty analysis. Finite time convergence of sliding manifolds were proved for independent controller modes to establish global convergence and robustness. Multiple Lyapunov Function approach was used to mathematically prove finite convergence of the switched system. Despite accessing only local information, the controller performs on par with popular existing planners like A* or wavefront algorithm that require global map and robot pose information. Furthermore, this reactive controller uses simple arithmetic computations for motion planning thus significantly reducing computation and power consumption. 

Simulations in ROS and Gazebo environment were performed to validate the efficiency and robustness of controller in static and moving target in the presence of fixed obstacle cluttered environments. The boundary following algorithms and exit condition work efficiently even with sharp corners of convex obstacles. The drawback of the controller is its inabilty to handle concave obstacles. The controller behaviour is similar that of tangent bug as illustrated by an experiment on unicycle type robot in the following video.

<div>
<iframe width="900" height="506" src="https://www.youtube.com/embed/QEmhKKyVBwU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

The experiments were conducted under the VICON Motion capture setup with a Firebird differential drive robot and Hokuyo laser scanner. In this experiment reactive controller has access only to coarse bearing data and 2D Lidar scan. Reactive controller was observed to handle dynamic obstacles in simulations and experiments elegantly bolstering the robustness property. A manuscript containing our research findings is under preparation. Further work could be extending the controller for concave shaped obstacles and developing controller for $\R^3$.

This [report](/assets/IITB_RI_report.pdf) contains partial details of research work accomplished which is yet to be published. The report contains also contains incomplete proofs and few preliminary simulation results. This report mainly focuses on expounding the details of practical implementation and specifically highlights practical implementations issues and how they were solved for simulations. This report is yet to finished due to tight time constraints and busy schedule. Code for Gazebo-ROS simulations can be found [here](https://github.com/ridhipuppala/reactiveplanner_ARMSLab).
