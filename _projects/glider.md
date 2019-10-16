---
layout:       project
date:         07 April 2019
title:        Novel underwater glider - Robuoy
caption:      Undergraduate Research
description:  >
 An undergraduate research project at Robotics Lab supervised by Prof. Asokan Thondiyath at IIT Madras
image:        /assets/img/project/glider.png
screenshot:
  src:        /assets/img/project/glider.png
  srcset:
    1920w:    /assets/img/project/glider.png
    960w:     /assets/img/project/glider.png
    480w:     /assets/img/project/glider.png
featured: true
#accent_color: '#ee682a'
#accent_image: /assets/img/sidebar-bg.jpg
---

*RoBuoy* is an underwater glider with a novel variable buoyancy mechanism conceptualized by Dr. Thiyagarajan Ranganathan. RoBuoy uses actuated metallic bellows to change the volume which makes the system simple and modular in construction without any compromise in the performance. It uses minimal number of parts compared to the existing gliders which reduces the overall complexity of the system. Also, most of the conventional gliders use the external fluid for its working which may result in corrosion or fouling of parts and requires frequent maintenance. In the proposed glider, all the vital parts required for its working, apart from the sensing payloads are enclosed inside the hull, thereby increasing the durability.

The preliminary design and system modelling work was published in [ICRA](https://ieeexplore.ieee.org/abstract/document/8462921). The following video explains the idea and working principle briefly.

<div class="videowrapper">
<iframe width="900" height="506" src="https://www.youtube.com/embed/XhX145jd3wA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## My Contribution

Initally, I rectified the dynamical model and correlated experimental trajectory data with dynamical simulation results. Major contribution has been in design optimization and performance evaluvation of glider through extensive simulations on the accurate dynamical model. The trajectories of glider varied significantly even with slight changes in fixed wing location (d) and area scale factor (σ) as illustrated by the following plot. 

![](cases.jpg)

Consequently, I set out to perform iterative simulations of glider varying d and σ in MATLAB dynamical simulations. I optimized design variables of d and σ with the cost function as gliding-range-to-depth ratio. The yellow shaded region in the following plot was identified as optimal working region for RoBuoy in the case where both linear acutators operate simultaneously.

![opt.png](opt.png)

Most exciting part of my work was to propose of a sequential switching algorithm using pitch feedback to achieve smooth and energy-efficient trajectories. Furthermore, I analyzed the different operating modes and proposed hybrid glider concept which uses an additonal water thruster to significantly increase range-to-depth ratio. A co-authored journal article expounding the entire reseach work is under preparation in collaboration with Dr. Thiyagarajan Ranganathan and Prof. Asokan Thondiyath. 
