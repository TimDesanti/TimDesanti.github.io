---
title: Welcome
tags:
- tag1
- tag2
---
<center>
<font size= "6">Tim Desanti Datasheet</font><br>
as part of<br>
<font size= "8"> Temperature Equalizing Blinds</font><br>
for<br>
<font size= "5"> Team 105 </font><br>

**Submission: October 31, 2025**
</center>

## Introduction
The Temperature Equalizing Blinds system is designed to automatically regulate room temperature by adjusting the position of window blinds in response to ambient conditions. Using a temperature sensor, the system detects heat variations and actuates a small 12 V DC motor, controlled through an H-bridge driver, to open or close the slats of the blinds. The goal is to maintain thermal balance by minimizing excessive sunlight during hot conditions and maximizing natural warmth during cooler periods.


### Project Summary

The motor control subsystem operates a small 12 V DC brushed motor through an H-Bridge driver (FAN8100N) to open and close the blinds. Controlled by the PIC18F57Q43 Curiosity Nano, it uses PWM signals to regulate motor speed and direction for smooth movement. A 9–12 V DC power source supplies the system, with voltage regulated to 5 V for control electronics. The design includes a status LED and connector interface for integration with the temperature sensing and main control modules.


### My Contribution

My part of the project focuses on designing and constructing the motor control subsystem that physically opens and closes the blinds based on input from the main control unit. It will rely on the other subsystems to determine how it will operate.


To review the details listed of the material used to construct the subsection, you can review it in the https://timdesanti.github.io/03-BOM/BOM/ section of the datasheet. 

For all the sections
