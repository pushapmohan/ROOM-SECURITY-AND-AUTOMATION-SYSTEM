# ROOM-SECURITY-AND-AUTOMATION-SYSTEM
ROOM SECURITY AND AUTOMATION SYSTEM
# Room Security and Automation System – Multisim Simulation

## Overview
This project presents the design and simulation of a **Room Security and Automation System** using **digital logic circuits** in **NI Multisim**. The system integrates **password-based door security**, **motion detection**, **temperature sensing**, and **automatic appliance control**, along with an **alarm system** for unauthorized access.

The project demonstrates practical implementation of **combinational and sequential logic**, making it suitable for understanding real-world security and automation concepts at the digital design level.

---

## Objectives
- To design a password-protected security system
- To detect incorrect access attempts and trigger an alarm
- To automate room appliances based on sensor inputs
- To apply combinational and sequential logic in a practical system

---

## System Features
- **Password-Based Door Access Control**
- **Correct / Incorrect Input Detection**
- **Motion Sensor–Based Automation**
- **Temperature Sensor–Based Appliance Control**
- **Alarm System for Unauthorized Access**
- **Digital Display for System Status**

---

## System Description

### 1. Password Verification Unit
- Uses **XNOR gates** to compare entered input bits with predefined correct values
- AND logic ensures all bits must match for correct access
- Produces:
  - **Correct Input signal**
  - **Incorrect Input signal**

---

### 2. Door Control Logic
- Door opens only when the correct password is entered
- Incorrect password triggers internal control logic for alarm activation

---

### 3. Sequential Control Unit
- Implemented using **JK Flip-Flops**
- Controls system states and timing
- Clocked using a **2 Hz clock signal**

---

### 4. Sensor-Based Automation
- **Motion Sensor**:
  - Detects presence in the room
  - Controls room lighting automatically
- **Temperature Sensor**:
  - Detects room temperature
  - Controls air conditioner operation

---

### 5. Alarm System
- Activated on:
  - Incorrect password input
  - Security violation
- Implemented using **AND / OR logic**
- Provides immediate alert for unauthorized access

---

### 6. Output Devices
- **Room Bulb** – Automatically controlled
- **Air Conditioner** – Temperature-dependent control
- **Alarm** – Security alert
- **Digital Display** – System status indication

---

## Logic Components Used
- XNOR Gates
- AND / OR Gates
- NOT Gates
- JK Flip-Flops
- Clock Generator
- Digital Display
- Logic Switches

---

## Simulation Details
- Designed and simulated in **NI Multisim**
- All system functionalities verified:
  - Password matching
  - Alarm triggering
  - Sensor-based appliance control
  - Sequential operation using flip-flops

---

## Tools Used
- NI Multisim
- Digital Logic Design
- Combinational and Sequential Circuits


---

## Learning Outcomes
- Understanding of digital security systems
- Practical use of combinational and sequential logic
- Integration of sensors with logic circuits
- State control using flip-flops
- Real-world automation concept simulation

---


## Author
**Pushap Mohan Sharma**  
B.Tech – 1st Year  
Microelectronics and VLSI  
NIT Kurukshetra

---


