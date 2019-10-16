---
layout:       project
date:         30 Nov 2018
title:        Slicing and Tool path planning
caption:      Course Project
description:  >
  CAD in Manufacturing (Course) and Prof. Sathyan Subbiah (Guide)
image:        /assets/img/project/cadim.jpg
screenshot:
  path:       /assets/img/project/cadim.jpg
  srcset:
    1920w:    /assets/img/project/cadim.jpg
    960w:     /assets/img/project/cadim.jpg
    480w:     /assets/img/project/cadim.jpg

coupro: true

---

This course aims to explain CAD in the context of manufacturing. There were several MATLAB assigments on wireframe modelling, geometrical modelling (NURBS and B-rep), feature identification, tool path planning and slicing algorithms. Each of the assignment provided an intuitive understanding of the theory taught in class. 

The project was mainly focused on implementing Fixed step Slicing algorithm and Tool path planning which was dependent on previous work done in assignments. I implemented algorithm for tool path planning of 3 axis CNC and integrated fixed step slicing algorithm with single layer contour development for given 3D component in input mesh file. 

###### Tool Path Planning

Simulated tool motion on random Bezier surface in MATLAB and generated video of animation. The following video illustrates the tool path planning on a random Bezier surface given as input.

<div class="videowrapper">
<iframe width="993" height="506" src="https://www.youtube.com/embed/s0krTeFidRs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

###### 3D object slicing algorithms implemented on a cone

![cone_sliced.jpg](cone_sliced.jpg)

Code for project can be found [here](https://github.com/ridhipuppala/CADinMfg).
