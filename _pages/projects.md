---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## EEG amplifier for long-term monitoring
### 2019
The project mainly aims towards creating a low power-EEG amplifier which can be made in house at low cost. Analog front end of the device contains buffer amplifiers to handle high impedance interface and an Analog-to-Digital Converter (ADC). Digital end contains a microcontroller, which saves the digital signals from ADC in the SD card and sends the signals to the mobile phone by Bluetooth for live visualization. 

[Digital End PCB design](https://github.com/Senthurbavan/EEG_amplifier_digitalEnd_PCB)
[Firmware Code](https://github.com/Senthurbavan/EEG_amplifier_firmware)


## Processor Design for Image Down-Sampling
### 2018
Designed a custom processor in FPGA for image down sampling. Instruction set architecture (ISR) is designed and verified with Matlab. The processor is implemented in FPGA, the image and instruction set to downsample an image by the factor 2 are sent to the FPGA by Matlab through UART interface, the results are sent back to Matlab and compared with a Matlab implementation of downsampling.

[FPGA design and Matlab code](https://github.com/Senthurbavan/Image_sampling_processor_design)


## Automatic Doorbell
### 2018
Developed an automatic doorbell to automatically detect the presence of a person at doorstep. We used passive infrared (PIR) sensors to detect heat radiation from humans. A sensor, which is mounted on the door and a portable receiver with speaker to play sound are connected with WIFI to play a sound when someone is at the doorstep.

[PCB Design](https://github.com/Senthurbavan/Automatic_doorbell)


## GPS navigated Robot
### 2017
Developed a GPS navigated mobile robot with microcontroller for Robot Design and Competition module. The task was that the robot should navigate to a given GPS goal location in a playground while avoiding obstacles on the way to pick a metal ring in a white box at the destination. The boxes are placed in the center of a white circle drawn on the ground. The robot uses a color sensor to detect the white circle and the white box. 

[Arduino code](https://github.com/Senthurbavan/GPS_navigated_robot)

Robot with three ultrasonic sensors for obstacle avoidance:
<p style="text-align:center;">
  Robot with three ultrasonic sensors for obstacle avoidance:
  <img src='/images/obstacle-avoidance-robot-scaled.jpeg' style="width:50%" class="center">
</p> 
<!-- <p style="text-align:center;"><img src='/images/obstacle-avoidance-robot-scaled.jpeg' style="width:50%" class="center"></p>  -->

White line detection, finding nearest bottle and move towards each nearest bottles:
<iframe style="width:50%" src="https://www.youtube.com/embed/7MHmC37A1u0" frameborder="0" allow="accelerometer; autoplay; clipboard-write;     encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>




## Analog Line Following Robot
### 2017
The aim of the project is to develop a line following robot without microcontroller and with analog electronic components. Employed IR emitter and receiver to detect difference in reflection from the surface to identify the white line on black surface. Designed a PID controller with operational amplifiers for motor speed control.  

[PCB Design](https://github.com/Senthurbavan/Analog_line_following_robot_PCB)

<img src='/images/analog_robot.jpeg' width='400'>

<iframe width="400" height="225" src="https://www.youtube.com/embed/CKTVevsehSA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>





