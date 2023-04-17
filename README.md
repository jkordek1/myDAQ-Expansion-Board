# myDAQ Expansion Board

<div align="center">
 
[![Tweet](https://img.shields.io/twitter/url/https/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=%F0%9F%93%A2%20Various%20README%20templates%20and%20tips%20on%20writing%20high-quality%20documentation%20that%20people%20want%20to%20read.&url=https://github.com/kylelobo/The-Documentation-Compendium)
[![Version](https://img.shields.io/github/v/release/jkordek1/myDAQ-Expansion-Board)](https://github.com/jkordek1/myDAQ-Expansion-Board/releases/tag/Initial)
[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/jkordek1/myDAQ-Expansion-Board)](https://github.com/jkordek1/myDAQ-Expansion-Board/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/jkordek1/myDAQ-Expansion-Board)](https://github.com/jkordek1/myDAQ-Expansion-Board/pulls)
 
 </div>
 
 Expansion board for NI myDAQ Student Data Acquisition Device, developed in 2022 for students studying at Zagreb university of applied sciences.
 It enables quick and easy.
 
 ## Features
 - Push buttons
 - Toggle switches
 - LEDs
 - BCD decoder for seven-segment display
 - L298n H-bridge used for powering two DC motors or one stepper motor
 - ACS712ELCTR-05B-T current sense IC for motor current measurement
 - External power supply for DC motors
 - Potentiometer
 - Light dependent resistor


<p align="center">
  <img width="800" src="https://raw.githubusercontent.com/jkordek1/myDAQ-Expansion-Board/main/Images/Front.jpg">
</p>

## Folder structure
    .
    ├── ...
    ├── 3DPrint                 # Files for 3D printing
    ├── Images                  # Images of the project
    ├── KiCADFiles              # Main folder
    │   ├── 3d models           # 3d models of components
    │   ├── Datasheet           # Datasheet collection
    │   ├── Graphics            # Custom graphics for PCB
    │   ├── gerber              # gerber output folder
    │   └── myDAQExpansionBoard # Main folder for KiCAD files
    └── ...
