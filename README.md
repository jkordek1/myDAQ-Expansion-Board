# myDAQ Expansion Board

[![Version](https://img.shields.io/github/v/release/jkordek1/myDAQ-Expansion-Board)](https://github.com/jkordek1/myDAQ-Expansion-Board/releases/tag/Initial)
[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/jkordek1/myDAQ-Expansion-Board)](https://github.com/jkordek1/myDAQ-Expansion-Board/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/jkordek1/myDAQ-Expansion-Board)](https://github.com/jkordek1/myDAQ-Expansion-Board/pulls)

 Expansion board for NI myDAQ Student Data Acquisition Device, developed in 2022 for students studying at Zagreb university of applied sciences.
 It enables quick and easy .VI development without the need of connecting different modules via breadboard and jumpers.
 
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

## Images
<p align="center">
  <img width="800" src="https://raw.githubusercontent.com/jkordek1/myDAQ-Expansion-Board/main/Images/Front.jpg">
</p>

## Project folder structure
    .
    ├── ...
    ├── 3DPrint                 # Files for 3D printing
    ├── Images                  # Images of the project
    ├── KiCADFiles              # Main folder
    │   ├── 3d models           # 3d models of components
    │   ├── Datasheet           # Datasheet collection
    │   ├── Graphics            # Custom graphics for PCB
    │   ├── gerber              # gerber output folder
    │   ├── myDAQExpansionBoard # Main folder for KiCAD files
    │   └── Schematic.pdf       # Project schematic
    └── ...
