---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

## EEG amplifier for long-term monitoring - 2019
The project mainly aims towards creating a low power-EEG amplifier which can be made in house at low cost. Analog front end of the device contains buffer amplifiers to handle high impedance interface and an Analog-to-Digital Converter (ADC). Digital end contains a microcontroller, which saves the digital signals from ADC in the SD card and sends the signals to the mobile phone by Bluetooth for live visualization. 

[Digital End PCB design](https://github.com/Senthurbavan/EEG_amplifier_digitalEnd_PCB)\
[Firmware Code](https://github.com/Senthurbavan/EEG_amplifier_firmware)

<!-- Analog frontend PCB design:\
<img src='/images/afe_design.png' style="width:75%">

\
Digital frontend PCB design:\
<img src='/images/dfe_design.png' style="width:40%">

\
Digital frontend PCB:\
<img src='/images/dfe_pcb.jpg' style="width:40%"> -->

## Processor Design for Image Down-Sampling - 2018
<!-- I designed an instruction set architecture based on RISC-V and wrote an instruction set for downsampling a 256x256 image using the nearest neighbor downsampling and weighted average filter. I designed the microarchitecture of a processor and built the simulation of the processor in MATLAB. Finally, I implemented the design in an FPGA and verified it with MATLAB results. -->

Designed a custom processor for image downsampling. Instruction set architecture was designed based on RISC-V and an instruction set was written for downsampling a 256x256 image using the nearest neighbor downsampling and weighted average filter. The ​​microarchitecture of a processor was designed and the simulation of the processor was built in MATLAB for verification. The processor was implemented in FPGA. The image and instruction set to downsample an image by factor 2 were sent to the FPGA by MATLAB through the UART interface for processing. The results were sent back to Matlab and compared with the MATLAB implementation of downsampling.

[FPGA design and Matlab code](https://github.com/Senthurbavan/Image_sampling_processor_design)

Schematic design of the Processor:\
<img src='/images/fpga_sch.png' style="width:75%">

\
Original and downsampled images:
<img src='/images/fpga_op.png' style="width:75%">

## Automatic Doorbell - 2018
Developed an automatic doorbell to automatically detect the presence of a person at doorstep. We used passive infrared (PIR) sensors to detect heat radiation from humans. A sensor, which is mounted on the door and a portable receiver with speaker to play sound are connected with WIFI to play a sound when someone is at the doorstep.

[PCB Design](https://github.com/Senthurbavan/Automatic_doorbell)


## GPS navigated Robot - 2017
Developed a GPS navigated mobile robot wth microcontroller for Robot Design and Competition module. The task was that the robot should navigate to a given GPS goal location in a playground while avoiding obstacles on the way to pick a metal ring in a white box at the destination. The boxes are placed in the center of a white circle drawn on the ground. The robot uses a color sensor to detect the white circle and the white box. 

[Arduino code](https://github.com/Senthurbavan/GPS_navigated_robot)

Robot with three ultrasonic sensors for obstacle avoidance:\
<img src='/images/obstacle-avoidance-robot-scaled.jpeg' style="width:50%">

\
White line detection, finding nearest bottle and move towards each nearest bottles:
<iframe width="200" height="125" src="https://www.youtube.com/embed/7MHmC37A1u0" frameborder="0" allow="accelerometer; autoplay; clipboard-write;     encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


## Analog Line Following Robot - 2017
The aim of the project is to develop a line following robot without microcontroller and with analog electronic components. Employed IR emitter and receiver to detect difference in reflection from the surface to identify the white line on black surface. Designed a PID controller with operational amplifiers for motor speed control.  

[PCB Design](https://github.com/Senthurbavan/Analog_line_following_robot_PCB)

PCB design of the robot:\
<img src='/images/analog_robot.jpeg' style="width:50%">

\
Robot on the track:
<iframe width="200" height="125" src="https://www.youtube.com/embed/CKTVevsehSA" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Other Fun Projects

### Alien Invation
[Python code](https://github.com/Senthurbavan/Alien_Invasion)
<img src='/images/pygame.gif' style="width:100%">


