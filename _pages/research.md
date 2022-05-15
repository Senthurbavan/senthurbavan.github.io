---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Low Power FPGA-based Hardware Accelerator for Autonomous Navigation of Mobile Robots

Power consumption is an important parameter in designing autonomous mobile robots (AMR), especially for time-constrained applications. Most AMRs use battery power for navigation and as a result, the runtime of such robots is often limited. In this work, I developed a hardware-software co-design architecture to optimize power consumption with high performance in navigational computations. The FPGA hardware accelerator is designed for the forward simulation part of the local planner of the ROS navigation stack and picking the best velocity command is implemented in the ARM processor in C++. Exploiting the possibilities of parallel computations in FPGA, multiple trajectories are simulated in parallel thus reducing computation time as well. Simulation and experiment results show that the resulting component is consuming less power to a degree of four and faster.

K. Senthurbavan, Peshala Jayasekara & Dilan Weerakkody. "Low Power FPGA-based Hardware Accelerator for Autonomous Navigation of Mobile Robots". In 2020 Australasian Conference on Robotics and Automation (ACRA 2020) ([Paper link](https://ssl.linklings.net/conferences/acra/acra2020_proceedings/views/includes/files/pap104s1-file1.pdf))

Overview of the system:\
<img src='/images/Overview.png' style="width:50%">
\
\
Overview of the hardware accelerator:\
<img src='/images/overview_hw_ip.png' style="width:75%"> 
\
\
Demonstration video:
<iframe width="560" height="315" src="https://www.youtube.com/embed/gDYCPDyNlkA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
