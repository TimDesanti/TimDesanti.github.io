---
title: Component Selection Tim Desanti 105
---


# **DC Motor**

1. **GEARMOTOR 35 RPM 12V MIRCO METAL**

   <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/182eab25-9bff-4002-9039-fb67696d1577" />


   * $37.95/each  
   * [Link to product](https://www.digikey.com/en/products/detail/pololu/3046/10450048)

   | Pros              | Cons                                |
   | ----------------- | ----------------------------------- |
   | 12v               | Expensive                           |
   | Small in size     | Might be too slow                   |
   | High torque       | Size may not be as compact as wanted|

---

2. **GEARMOTOR 200 RPM 3–6V DC**

   <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/2ceb7257-6a29-4b6e-a94b-e67cd63d4f13" />

   * $2.95/each  
   * [Link to product](https://www.digikey.com/en/products/detail/adafruit-industries-llc/3777/8687221)

   | Pros            | Cons          |
   | ---------------- | ------------- |
   | Low voltage use  | More expensive |
   | Compact          | Weak          |
   | Simple wiring    | Low RPM       |

---

3. **SERVOMOTOR RC 4.8V**

   <img width="200" height="200" alt="image" src="https://github.com/user-attachments/assets/90d04205-5d41-4f75-ae2f-dc2e91027256" />

   * $3.62/each  
   * [Link to product](https://www.digikey.com/en/products/detail/dfrobot/SER0006/7597224)

   | Pros                                  | Cons                       |
   | ------------------------------------- | --------------------------- |
   | Quick response time                   | Requires programming        |
   | Precise movement                      | Moderately expensive        |
   | Programmable to move to set positions | Requires more voltage       |

---

**Choice:** Option 1 — *GEARMOTOR 35 RPM 12V MICRO METAL*

**Rationale:**  
Requires fewer programs to be made. It will rely on the sensors to function, which is what we want. Provides enough power to run its function at a reasonable cost. High Torque.

---

# **H-Bridge Motor**

1. **IC MOTOR DRIVER 12V-52V 24SO**

  ![24-SOIC_sml](https://github.com/user-attachments/assets/e3ee7cb9-d6fa-422f-990f-9d7dc340104b)


   * $6.16/each  
   * [Link to product ](https://www.digikey.com/en/products/detail/stmicroelectronics/L6235D013TR/715921)
   | Pros                      | Cons                                                             |
   | -------------------------- | ---------------------------------------------------------------- |
   | Inexpensive                | Requires external components and support circuitry               |
   | For large voltage    |      complicated configuration                                                          |
   | 12V             | surface mount                                    |

---

2. **L9110H H-BRIDGE 8DIP MOTOR DRIVE**

   ![8-DIP_sml](https://github.com/user-attachments/assets/ff2741e7-e249-4a49-bef6-e16c40165093)


   * $1.50/each  
   * [Link to product](https://www.digikey.com/en/products/detail/adafruit-industries-llc/4489/11594498?s=N4IgTCBcDaILYHsAuCBOACAxggdk1CANugIYAmJAZqgK4CWSIAugL5A)

   | Pros                      | Cons                                                             |
   | -------------------------- | ---------------------------------------------------------------- |
   | Inexpensive                | Requires external components and support circuitry               |
   | easy to set up    | can only run 1 motor                                 |
   | 8-dip       |                                                                  |

---

3. **IC MTR DRV BIPLR 12-55V TO220-11**

  
![14-TO-220-11 nonisolated staggered and bent_sml](https://github.com/user-attachments/assets/3787d342-8237-49d6-bdc5-6a3a4398d1d2)

   * $28.26/each  
   * [Link to product](https://www.digikey.com/en/products/detail/texas-instruments/LMD18201T-NOPB/148220)

   | Pros                                                   | Cons                                                             |
   | ------------------------------------------------------ | ---------------------------------------------------------------- |
   | ECAD                                                   | Expensive                                                         |
   | 12V-55V                                                | Complicated wiring                                               |
   | Can run 2 different motors                             | Fixed output voltage                                             |

---

**Choice:** Option 2 - *L9110H H-BRIDGE 8DIP MOTOR DRIVE*

**Rationale:**  
A simple H-bridge for 1 motor, which is being used for the system. Easier to wire up and to code. Small and inexpensive, great for simple coding and space constraints. 

---

## **Overview Summary**

Microchip PIC18F57Q43 Curiosity Nano, Analog Input Sensor, Green LED, and Connectors are parts that were given and worked on in class.  
The only unfamiliar part would be the DC motor and the H-Bridge, as they are not familiar components but are used in the same way as components we have worked on in the classroom.


