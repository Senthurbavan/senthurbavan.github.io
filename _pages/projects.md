---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

EEG amplifier for long-term monitoring
======
2019
The project mainly aims towards creating a low power-EEG amplifier which can be made in house at low cost. Analog front end of the device contains buffer amplifiers to handle high impedance interface and an Analog-to-Digital Converter (ADC). Digital end contains a microcontroller, which saves the digital signals from ADC in the SD card and sends the signals to the mobile phone by Bluetooth for live visualization. 
[Digital End PCB design](https://github.com/Senthurbavan/EEG_amplifier_digitalEnd_PCB)
[Firmware Code](https://github.com/Senthurbavan/EEG_amplifier_firmware)

Processor Design for Image Down-Sampling
======
2018
Designed a custom processor in FPGA for image down sampling. Instruction set architecture (ISR) is designed and verified with Matlab. The processor is implemented in FPGA, the image and instruction set to downsample an image by the factor 2 are sent to the FPGA by Matlab through UART interface, the results are sent back to Matlab and compared with a Matlab implementation of downsampling.

[FPGA design and Matlab code](https://github.com/Senthurbavan/Image_sampling_processor_design)
