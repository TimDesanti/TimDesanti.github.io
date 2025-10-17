---
title: Component Selection Tim Desanti 105
---

## Examples

### Style 1

> This is the example found in the assignment, which uses more HTML

*Table 1: Example component selection*

**External Clock Module**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](image1.png)<br>Option 1.<br> XC1259TR-ND surface mount crystal<br>$1/each<br>[link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366)                 | \* Inexpensive[^1]<br>\* Compatible with PSoC<br>\* Meets surface mount constraint of project                                               | \* Requires external components and support circuitry for interface<br>\* Needs special PCB layout. |
| ![](image3.png)<br>\* Option 2. <br>\* CTX936TR-ND surface mount oscillator <br>\* $1/each <br>\* [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940) | \* Outputs a square wave <br>\* Stable over operating temperature <br> \* Direct interface with PSoC (no external circuitry required) range | * More expensive <br>\* Slow shipping speed                                                         |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.

### Style 2

> Also acceptable, more markdown friendly

**Motion Sensor**

1. HC-SR505 PIR Motion Sensor Module

    ![HC-505-Mini-PIR-Motion-Sensor-Module](https://github.com/user-attachments/assets/eab76275-a83a-420e-9258-f99128310ef1)


    * $1.95/each
    * [link to product](https://protosupplies.com/product/hc-sr505-mini-pir-motion-sensing-module/)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | Senses Body heat within 9ft-12ft          | Needs special PCB layout.                                        |
    | Uses very low power                       | 

2. ALTA WIRELESS INFRARED MOTION SE

    ![MFG_MNS2-9-W2-MS-IR_sml](https://github.com/user-attachments/assets/6a433689-7f32-4620-b8aa-2ef463277a93)


    * $116.60/each
    * [Link to product](https://www.digikey.com/en/products/detail/monnit-corporation/MNS2-9-W2-MS-IR/7776952)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | uses inferred to detect people                                    | More expensive      |
    | Wireless                                                          | Larger item         |
    | More coverage (1000ft)                                            | difficult to wire with system

   3. MOTION DETECTION RADAR SWITCH

    ![MFG_IMD-3000-Series_sml](https://github.com/user-attachments/assets/ff408c59-6127-48e3-9669-798a049a8b21)


    * $50.26/each
    * [link to product](https://www.digikey.com/en/products/detail/innosent-gmbh/80-00000450/13182472)]

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | quick response time                       | Requires external components and support circuitry for interface |
    | More accurate body heat reads             | moderately expensive                                             |
    | can be used outdoors                      | requires more voltage

**Choice:** Option 1: HC-SR505 PIR Motion Sensor Module

**Rationale:** The data sheet provides a C code program that is Arduino compatible. Much more affordable and compact, they can be soldered or wired to a breadboard or circuit. The distance may be limited, but it is within reason if used inside.


**Voltage regulator**

1. IC REG BUCK BOOST ADJ 1.5A 8SOIC

   ![31~8SOIC-3](https://github.com/user-attachments/assets/79a5d0b8-587e-43c4-ab3a-1e7bf68ff89e)


    * $0.29/each
    * [link to product](https://www.digikey.com/en/products/detail/diodes-incorporated/AZ34063UMTR-G1/4471007)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | minimum number of external components.    |                                                                  |
    | built-in timer                            | uses more than 3V to operate



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

**Choice:**  IC REG BUCK BOOST ADJ 1.5A 8SOIC
**Rationale:** A familiar part we worked with, more compatible with the microcontroller, cheaper, and is more simple to wire and code. By having
something we used before, it should save time working on a project, as it is a product that is not new to learn. 
