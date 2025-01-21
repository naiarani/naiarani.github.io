---
layout: archive
title: "Course Projects"
permalink: /classprojects/
author_profile: true
classes: wide
---

Welcome to the course projects page! Here's a quick overview of what each project is about.

## 2-Link Manipulator in Space

For my final project for MMAE 540: Robotics, I developed the dynamics and preesent various methods of control for a 2-link
manipulator arm attatched to a satellite bus in a zero-gravity environment. I used Matlab to develop the simulations, and explored PD, Adaptive Control, and MPC controllers. You can see my GitHub repo [here](https://github.com/naiarani/MMAE540-FinalProject).

<div style="text-align: center; margin-bottom: 30px;">
  <img src="{{ site.baseurl }}/assets/images/540project" alt="540project" style="max-width: 100%; height: auto">
</div>

## GNSS Spoofing Detection Method - Covariance Analysis

As part of my research lab I have been able to learn and contribute some work towards defining a measurement space for detection of GNSS spoofing detection. A highlight of this project has been learning a lot about GPS, other navigation methods such as LiDAR and IMUs, estimation, signal processing, and more! I use Matlab to conduct these Monte Carlo tests

<div style="text-align: center; margin-bottom: 30px;">
  <img src="{{ site.baseurl }}/assets/images/researchexample.png" alt="research" style="max-width: 100%; height: auto">
</div>


## Reinforcement Learning for Calico based on AlphaZero

For my final project for MMAE 549: Optimal Control, I attempted to develop a board game environment and use reinforcement learning techniques, based on AlphaGo Zero, to train a model to beat human players. AlphaGo Zero was the first machine learning algorithm to beat human professionals without any apriori data. The model aims to train a convolutional neural network (CNN) with Monte Carlo Tree Search (MCTS). My project focused on creating a board game environment in Python, similar to Calico, and adapting this algorithm to play the game environment. 

I attempted various methods to test and implement the objective, integrating the SIMPLE github library, using farma’s gymnasium API, starting from scratch and following other’s AlphaZero structures, and implementing a simplified MCTS (without policy iteration from CNN) with a simpler existing game environment. Majority of my work was spent on attempting to create my own game environment to work with the structures of other MCTS and AlphaZero implementations.


## Investigating Solar Coronal Temperatures Through GOES-U Observations

Abstract: This group project aimed to investigate the phenomena that is the significant discrepancy
between the solar corona’s high temperatures compared to the effective temperature
of the Sun. Utilizing data from GOES-19, COR3, and COR2, we attempt to conduct an analysis on the relationship between solar
radiation emissions in the form of X-Ray flux and measured coronal temperatures via electron density profiles. We use Sun.py to test the correlation
of solar activity via the fluctuations of X-ray activity, the change in sun spots, and the proton density.



