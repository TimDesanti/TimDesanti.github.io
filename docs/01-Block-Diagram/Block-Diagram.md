---
title: Individual Block Diagram for Slat Motor
tags: 
- tag1
- tag2
---

## Overview
This block diagram illustrates the system architecture for controlling a DC motor using the Microchip PIC18F57Q43 Curiosity Nano board. It shows how power, sensing, and actuation are distributed throughout the system. A 12V 3A unregulated power supply provides the main power, which is regulated to 12V (1.5A) for the microcontroller and control electronics. An analog sensor connected to the ADC input (RA0) provides input signals for feedback or control. The H-Bridge (FAN8100N) drives the motor (actuator) using PWM signals from the microcontroller. Green LED to check if power is going through the system. It translates to a motor that will open and close the blinds depending on the signals given from the other components.


## Motor PCB Block Diagram 

<img width="741" height="901" alt="Individual Block EGR304 TND drawio" src="https://github.com/user-attachments/assets/d1fc3d9e-a973-4d93-8bf1-afc0cce7d744" />




