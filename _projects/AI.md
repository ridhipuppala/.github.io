---
layout:       project
date:         30 May 2018
title:        Neural network (NN) based fastener sorting
caption:      Course Project 
description:  >
  Artificial Intelligence in Manufacturing (Course) and Prof. Samuel G.L. (Guide)
image:        /assets/img/project/ai.png
screenshot:
  path:       /assets/img/project/ai.png
  srcset:
    1920w:    /assets/img/project/ai.png
    960w:     /assets/img/project/ai.png
    480w:     /assets/img/project/ai.png
coupro: true
---

The project explores the practical applications of machine vision in fastener or part sorting operations in automobile recycling plants, manufacturing lines and warehouse logistics. In the project a neural network classifier was trained with 5 classes of fasteners (T-nut, T-bolt, countersunk bolt,bearing,hexnut) achieving 91% testing accuracy! Most challening part was to generate dataset as datasets for these classes were not available online. I used OpenCV morphlogical transformation functions to perform image augentation of 100+ smartphone images of parts to generate 1500 image data set. I also proposed dimensional measurement and feature extraction of classified part in restricted environmental settings with direct applications in automobile manufacturing and recycling lines. I demonstrated dimensional measurements of the classified parts using countour detection, edge detection under calibrated settings using Python OpenCV library. I refreshed my object oriented programming skills in Python while scripting my own functions for neural network classifier. I shifted to TensorFlow codes later which reduced code from 400 lines to 50 lines and significantly reduced training and execution time to just a few seconds. It bolstered my knowledge of computer vision algorithms, neural network architectures and processes of training and testing, and OpenCV concepts.

You can read more about the project in this [presentation](/assets/VR_ppt.pdf). Code is available [here](https://github.com/ridhipuppala/fastener_classifier).

## Fuzzy logic project

A mini project as a part of this course was on developing Fuzzy logic inference mechanism for Abrasive water jet machining data. Detailed report can be found [here](/assets/fuzzy_report.pdf).

## Nearest neighbour and k-Means Clustering algorithms

A small assignment on implementing k-Means and nearest neighbour clustering algoritms in MATLAB was an exciting task. The following image represents the result of the clustering algorithm.

![cluster.png](cluster.png)
