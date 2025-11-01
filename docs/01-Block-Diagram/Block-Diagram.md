---
title: Individual Block Diagram for Slat Motor
tags: 
- tag1
- tag2
---

## Overview
This block diagram illustrates the system architecture for controlling a DC motor using the Microchip PIC18F57Q43 Curiosity Nano board. It shows how power, sensing, and actuation are distributed throughout the system. A 9V 3A unregulated power supply provides the main power, which is regulated to 5V (1.5A) for the microcontroller and control electronics. An analog sensor connected to the ADC input (RA0) provides input signals for feedback or control. The H-Bridge (FAN8100N) drives the motor (actuator) using PWM signals from the microcontroller. Green LED to check if power is going through the system. It translates to a motor that will open and close the blinds depending on the signals given from the other components.


## Blind Slats PCB Block Diagram 
<img width="1274" height="1158" alt="image" src="https://github.com/user-attachments/assets/30b9696d-8eb2-4841-80f3-8173a1732f59" />




