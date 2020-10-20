---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Pixel-Wise Motion Deblurring of Thermal Videos

Uncooled microbolometers can enable robots to see in the absence of visible illumination by imaging the “heat” radiated from the scene. Despite this ability to see in the dark, these sensors suffer from significant motion blur. This has limited their application on robotic systems. As described in this paper, this motion blur arises due to the thermal inertia of each pixel. This has meant that traditional motion deblurring techniques, which rely on identifying an appropriate spatial blur kernel to perform spatial deconvolution, are unable to reliably perform motion deblurring on thermal camera images. To address this problem, this paper formulates reversing the effect of thermal inertia at a single pixel as a Least Absolute Shrinkage and Selection Operator (LASSO) problem which we can solve rapidly using a quadratic programming solver. By leveraging sparsity and a high frame rate, this pixel-wise LASSO formulation is able to recover motion deblurred frames of thermal videos without using any spatial information. To compare its quality against state-of-the-art visible camera based deblurring methods, this paper eval- uated the performance of a family of pre-trained object detectors on a set of images restored by different deblurring algorithms. All evaluated object detectors performed systematically better on images restored by the proposed algorithm rather than any other tested, state-of-the-art methods. [[Paper](https://arxiv.org/abs/2006.04973)][[Website](https://fcav.engin.umich.edu/papers/pixelwise-deblurring)]

## Feature-constrained Active Visual SLAM for Mobile Robot Navigation

This project focuses on tracking failure avoidance during vision-based navigation to a desired goal in unknown environments. While using feature-based Visual Simultaneous Localization and Mapping (VSLAM), continuous identification and association of map points are required during motion. Thus, we discuss a motion planning framework that takes into account sensory constraints for a reliable navigation. We use information available in the SLAM and propose a data-driven approach to predict the number of map points associated in a given pose. Then, a distance-optimal path planner utilizes the model to constrain paths such that the number of associated map points in each pose is above a threshold. We also include an online mapping of the environment for collision avoidance. Overall, we propose an iterative motion planning framework that enables real-time replanning after the acquisition of more information. Experiments in two environments demonstrate the performance of the proposed framework. [[Paper](/files/ICRA_2018.pdf)] [[Demo Video](https://youtu.be/b4t_0nNq49c)] [[Code](https://github.com/XinkeAE/Active-ORB-SLAM2.git)]  



