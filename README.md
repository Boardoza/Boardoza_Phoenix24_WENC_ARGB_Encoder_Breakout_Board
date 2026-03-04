# Boardoza Phoenix-24WENC – Breakout Board

The **Boardoza Phoenix-24WENC** is a versatile **addressable RGB LED breakout board** designed for interactive lighting applications. It integrates **24 addressable ARGB LEDs** along with a **rotary encoder**, enabling users to control lighting effects dynamically through physical input.

This board is well-suited for **user interfaces, decorative lighting, visual feedback systems, and interactive prototypes**. With support for **both CMOS and TTL logic levels** and flexible **THT and SMD connection options**, it can be easily integrated into a wide range of embedded systems, from quick prototyping setups to final product designs.

## [Click here to purchase!](https://www.ozdisan.com/ureticiler/boardoza)
| Front Side | Back Side |
|:---:|:---:|
| ![Phoenix-24WENC Front](./assets/Phoenix-24WENC%20Front.png) | ![Phoenix-24WENC Back](./assets/Phoenix-24WENC%20Back.png) |

---

## Key Features

- **24 Addressable ARGB LEDs:** Provides vibrant, individually controllable RGB lighting for dynamic visual effects.  
- **Integrated Rotary Encoder Support:** Enables real-time and interactive LED control through user input.  
- **CMOS & TTL Logic Compatibility:** Ensures compatibility with a wide range of microcontrollers and logic systems.  
- **Flexible Signal Routing:** Includes DIN, CIN, DOUT, and COUT connections for easy signal chaining and management.  
- **Dual Connection Options:** Supports both THT (Through-Hole) and SMD (Surface-Mount) connections for flexible integration.  
- **Interactive Lighting Capabilities:** Ideal for user interfaces, visual feedback, and decorative lighting systems.  

---

## Technical Specifications

**Model:** Phoenix-24WENC   
**Manufacturer:** Boardoza  
**Functions:** Addressable RGB LED control with rotary encoder input  
**Input Voltage:** 3.3 V / 5 V  
**LED Model:** T3A33BRG-H9C0002X1U1930  
**Number of LEDs:** 24  
**LED Type:** Individually addressable RGB LEDs  
**Logic Compatibility:** TTL & CMOS  
**Data Interface:** Serial Data & Clock (DIN / CIN / DOUT / COUT)   
**Encoder Outputs:** Terminal A, Terminal B, Switch (Active Low)  
**Daisy-Chain Support:** Yes   
**Operating Temperature:** -40 °C to +85 °C  
**Board Dimensions:** 65.93 mm × 66.18 mm  

---

## Board Pinout

### **( J1 ) Power Connector**

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 1 | VCC | Power Supply |

### **( J2 ) Power Connector**

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 2 | VCC | Power Supply |

### **( J3 ) Encoder Terminal B**

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 3 | Terminal_B | Encoder B terminal output |

### **( J4 ) Encoder Terminal A**

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 4 | Terminal_A | Encoder A terminal output |

### **( J5 ) Encoder Switch**

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 5 | SW | Encoder switch output (Active Low) |

### **( J6 ) Data Output**

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 6 | DOUT | Series data output |

### **( J7 ) Clock Output**

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 7 | COUT | Clock output |

### **( J8 ) Data Input**

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 8 | DIN | Series data input |

### **( J9 ) Clock Input**

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 9 | CIN | Clock input |

### **( J10 ) Ground**

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 10 | GND | Ground |

### **( J11 ) Ground**

| Pin Number | Pin Name | Description |
|:---:|:---:|---|
| 11 | GND | Ground |

---

## Board Dimensions

![Board Dimensions](./assets/Phoenix-24WENC%20Dimensions.png)

---

## Step Files

[Boardoza Phoenix-24WENC.step](./assets/Phoenix-24WENC%20Step.step)

---

## Datasheets

- [T3A33BRG ARGB LED Datasheet](./assets/Phoenix-24WENC%20Datasheet.pdf)  
- [Rotary Encoder Datasheet](./assets/Rotary%20Encoder%20Datasheet.pdf)

---

## Version History

- V1.0.0 – Initial Release

---

## Support

- If you have any questions or need support, please contact **support@boardoza.com**

---

## **License**

This repository contains both hardware and software components:

### **Hardware Design**

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

All hardware design files are licensed under [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

### **Software/Firmware**

[![BSD-3-Clause][bsd-shield]][bsd]

All software and firmware are licensed under [BSD 3-Clause License][bsd].

[bsd]: https://opensource.org/licenses/BSD-3-Clause
[bsd-shield]: https://img.shields.io/badge/License-BSD%203--Clause-blue.svg
