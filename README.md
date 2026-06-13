# Ladder Logic for Micro Injection Moulding Machine

## Overview

This repository contains the PLC ladder logic program developed for a **Micro Injection Moulding Machine**. The system is designed to automate small-scale plastic component manufacturing using PLC and HMI-based control, temperature regulation, motor control, and pneumatic actuation.

The project focuses on providing an affordable solution for educational institutions, research laboratories, prototyping centers, and low-volume manufacturing applications.

---

## Features

### PLC Automation

* Automatic operation mode
* Manual operation mode
* Process sequencing and interlocking
* Machine status monitoring

### Temperature Control

* K-Type thermocouple feedback
* Heater ON/OFF control through SSR
* Temperature setpoint control
* Over-temperature protection

### Motor Control

* Forward motor operation
* Reverse motor operation
* Electrical interlocking
* Thermal overload protection

### Pneumatic Control

* Injection cylinder control
* Solenoid valve operation
* Adjustable process timing

### HMI Integration

* Start/Stop controls
* Temperature monitoring
* Alarm indication
* Process status display
* Parameter setting

### Safety Functions

* Emergency stop handling
* Overload protection
* Heater fault monitoring
* System interlocks

---

## Hardware Used

| Component          | Description               |
| ------------------ | ------------------------- |
| PLC                | Delta DVP32ES200R         |
| HMI                | Delta DOP Series          |
| Temperature Module | Delta DVP04TC             |
| Sensor             | K-Type Thermocouple       |
| Heater Control     | Solid State Relay (SSR)   |
| Motor Control      | Schneider Contactors      |
| Protection         | Thermal Overload Relay    |
| Actuation          | Pneumatic Solenoid Valves |
| Heating            | Band Heater               |
| Power Protection   | MCB                       |

---

## Software Used

* WPLSoft
* DOPSoft

---

## Process Flow

1. Power ON System
2. Initialize PLC
3. Read Temperature
4. Heat Barrel to Set Temperature
5. Wait Until Target Temperature Reached
6. Start Injection Cycle
7. Perform Material Injection
8. Hold Pressure
9. Return Mechanism
10. Complete Cycle
11. Ready for Next Operation

---

## Applications

* Educational Training
* Research & Development
* Product Prototyping
* Small Batch Manufacturing
* Plastic Product Testing
* Low Volume Production

---

## Advantages

* Low machine investment
* Compact machine footprint
* Reduced power consumption
* Easy operation and maintenance
* Suitable for small batch production
* Faster prototype development
* Consistent product quality

---

## Repository Contents

```text
├── FINAL LADDER FOR MICROMOLD.pdf
├── Screenshots
├── HMI Files
├── Wiring Diagrams
└── README.md
```

---

## Future Improvements

* IoT Monitoring
* Remote HMI Access
* Production Data Logging
* Automatic Fault Diagnostics
* Energy Consumption Monitoring

---

## Author

**Tharun CJ**

Micro Injection Moulding Machine Automation Project 

---

### License

This project is provided for educational and research purposes. Feel free to study, modify, and improve the design.
