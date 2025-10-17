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

    ![](<img width="640" height="640" alt="image" src="https://github.com/user-attachments/assets/c1c46e83-8249-479f-b8fe-801d135dd95e" />)

    * $1.95/each
    * [link to product](https://protosupplies.com/product/hc-sr505-mini-pir-motion-sensing-module/)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | Senses Body heat within 9ft-12ft          | Needs special PCB layout.                                        |
    | Uses very low power                       | 

2. ALTA WIRELESS INFRARED MOTION SE

    ![](<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/7e0766e9-71f6-468e-9be0-febff88cc165" />)

    * $116.60/each
    * [Link to product](https://www.digikey.com/en/products/detail/monnit-corporation/MNS2-9-W2-MS-IR/7776952)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | uses inferred to detect people                                    | More expensive      |
    | Wireless                                                          | Larger item         |
    | More coverage (1000ft)                                            | difficult to wire with system

   3. MOTION DETECTION RADAR SWITCH

    ![](<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/ee01a59e-437c-4ba2-a87f-a9aa27466038" />)

    * $50.26/each
    * [link to product]([[https://protosupplies.com/product/hc-sr505-mini-pir-motion-sensing-module/](https://www.digikey.com/en/products/detail/innosent-gmbh/80-00000450/13182472)](https://www.digikey.com/en/products/detail/innosent-gmbh/80-00000450/13182472))

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | quick response time                       | Requires external components and support circuitry for interface |
    | More accurate body heat reads             | moderately expensive                                             |
    | can be used outdoors                      | requires more voltage

**Choice:** Option 1: HC-SR505 PIR Motion Sensor Module

**Rationale:** The data sheet provides a C code program that is Arduino compatible. Much more affordable and compact, they can be soldered or wired to a breadboard or circuit. The distance may be limited, but it is within reason if used inside.


**Voltage regulator**

1. IC REG BUCK BOOST ADJ 1.5A 8SOIC

    ![](<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/a96476c3-98e4-4bef-88f7-128437615a10" />
)

    * $0.29/each
    * [link to product](https://www.digikey.com/en/products/detail/diodes-incorporated/AZ34063UMTR-G1/4471007)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | minimum number of external components.    |                                                                  |
    | built-in timer                            | uses more than 3V to operate



2. IC REG LINEAR 5V 1.5A TO220

    ![](<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/d6bb1a13-87c9-477a-9c0c-10387879de37" />
)

    * $0.50/each
    * [link to product]([https://www.digikey.com/en/products/detail/diodes-incorporated/AZ34063UMTR-G1/4471007](https://www.digikey.com/en/products/detail/stmicroelectronics/L7805CV/585964)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | minimum number of external components.    | requires a minimum voltage of 5V                                 |
    | PCB layout available                      | 
   






3. IC LNR REG CTRLR 1OUT 8DIP

    ![](<img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/efc4e4bd-cb04-4a98-a0c2-ba60caad03a8" />
)

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
