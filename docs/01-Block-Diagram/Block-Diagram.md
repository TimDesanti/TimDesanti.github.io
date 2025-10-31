---
title: Individal Block Diagram for Slat Motor
tags: 
- tag1
- tag2
---

## Overview
This block diagram illustrates the system architecture for controlling a DC motor using the Microchip PIC18F57Q43 Curiosity Nano board. It shows how power, sensing, and actuation are distributed throughout the system. A 9V 3A unregulated power supply provides the main power, which is regulated to 5V (1.5A) for the microcontroller and control electronics. An analog sensor connected to the ADC input (RA0) provides input signals for feedback or control. The H-Bridge (FAN8100N) drives the motor (actuator) using PWM signals from the microcontroller. Green Led it to check if power is going through the stystem. It translate to a motor that will open and close the blinds depending on the singnals given from the other components.


## Blind Slats PCB Block Diagram 
<img width="1282" height="1184" alt="image" src="https://github.com/user-attachments/assets/dd36bc1d-e63d-4627-a350-bb649f0561dd" />


