---
title: Component Selection Tim Desanti 105
---


**DC Motor**

1. GEARMOTOR 100 RPM 12V METAL

   <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/a2ebb640-b700-45e1-a3cc-9bf42f43ed35" />




    * $11.90/each
    * [link to product](https://www.digikey.com/en/products/detail/dfrobot/FIT0492-B/7087168?)

    | Pros                                      | Cons                                                           |
    | ----------------------------------------- | -------------------------------------------------------------- |
    | moderly expensive                         | meant for high torque                                          |
    | small in size                             | Might be too slow                                              |
    | meant for high torque                     | Size may not be as compact as wanted                           |

2. GEARMOTOR 200 RPM 3-6V DC

    <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/2ceb7257-6a29-4b6e-a94b-e67cd63d4f13" />


    * $2.95/each
    * [Link to product](https://www.digikey.com/en/products/detail/adafruit-industries-llc/3777/8687221)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Low voltage use                                                   | More expensive      |
    | Compact                                                           | Weak                |
    | Simple wiring                                                     | Low RPM             |        

   3. SERVOMOTOR RC 4.8V

   <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/90d04205-5d41-4f75-ae2f-dc2e91027256" />


    * $3.62/each
    * [link to product](https://www.digikey.com/en/products/detail/dfrobot/SER0006/7597224)

    | Pros                                      | Cons                                                           |
    | ----------------------------------------- | -------------------------------------------------------------- |
    | quick response time                       | Have to create a program                                       |
    | percise movement                          | moderately expensive                                           |
    | programmable to move to certain positions | requires more voltage

**Choice:** Option 1: GEARMOTOR 100 RPM 12V METAL

**Rationale:** Requires fewer programs to be made. It will rely on the sensors to function, which is what we want. Provides enough power to
run its function at a reasonable cost.

**Voltage regulator**

1. IC REG BUCK BOOST ADJ 1.5A 8SOIC

   ![31~8SOIC-3](https://github.com/user-attachments/assets/79a5d0b8-587e-43c4-ab3a-1e7bf68ff89e)


    * $0.29/each
    * [link to product](https://www.digikey.com/en/products/detail/diodes-incorporated/AZ34063UMTR-G1/4471007)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | minimum number of external components.    |                                                                  |
    | built-in timer                            | uses more than 3V to operate                                     |



2. IC REG LINEAR 5V 1.5A TO220

    ![497~TO220-3TO220AB~~3_sml](https://github.com/user-attachments/assets/287a036d-0502-41a2-8303-bae58bfbc862)


    * $0.50/each
    * [link to product](https://www.digikey.com/en/products/detail/stmicroelectronics/L7805CV/585964)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | minimum number of external components.    | requires a minimum voltage of 5V                                 |
    | PCB layout available                      | 
   






3. IC LNR REG CTRLR 1OUT 8DIP

   ![505~05-08-1510~N,N8~8_sml(200x200)](https://github.com/user-attachments/assets/1271e721-f886-48c1-9324-939288974429)


    * $8.52/each
    * [link to product](https://www.digikey.com/en/products/detail/analog-devices-inc/LT1575CN8-5-PBF/962848)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Low voltage drops                         | Requires external components and support circuitry for interface |
    | accommodate any required microprocessor power supply voltage    | requires a minimum voltage of 5V                                 |
    | PCB layout available                      | fixed output voltage

**Choice:**  IC REG LINEAR 5V 1.5A TO220

**Rationale:** A familiar part we worked with, more compatible with the microcontroller, cheaper, and simpler to wire and code. By having
something we used before, it should save time working on a project, as it is a product that is not new to learn. 

## Overview Summary
Microchip PIC18F57Q43 Curiosity Nano, Analog Input Sensor, H-Bridge Motor Driver, Green LED, and Connectors are parts that were given and worked on in class. The only unfamiliar part would be the DC motor, which will need a component selection. 

