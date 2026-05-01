# CubeSat System

Grant-funded capstone project focused on the design and integration of multi-layer PCBs for satellite subsystems.

This repository contains visual documentation only. Full design files are restricted.

---

## System Overview
Complete CubeSat assembly showing integrated avionics, control, and payload subsystems.

<p align="center">
  <img src="images/sattelite whole.jpeg" height="300"/>
</p>

---

## Motor Driver Board

High-power motor control board designed for satellite actuation, supporting BLDC operation and closed-loop control.

### Key Features
- 6-layer PCB stackup for power integrity and routing density  
- High-current BLDC phase routing  
- Integrated current sensing and hall sensors for FOC control  
- Dual STM32 microcontroller architecture  

### 3D Views
<p align="center">
  <img src="images/motor-top.png" height="250"/>
  <img src="images/motor-bottom.png" height="250"/>
</p>

### Physical Board
<p align="center">
  <img src="images/front and back motor board.jpeg" height="250"/>
</p>

### Routing Overview
<p align="center">
  <img src="images/motor_routing.png" height="250"/>
</p>

---

## Control Board (ADCS)

Attitude Determination and Control System (ADCS) board integrating multiple sensors and communication buses for spacecraft orientation and control.

### Key Features
- Multi-sensor integration (IMU, gyro, magnetometer)  
- I2C and SPI communication architecture  
- Compact layout within CubeSat volume constraints  
- Integrated power regulation and filtering  

### 3D Views
<p align="center">
  <img src="images/adcs-top.png" height="250"/>
  <img src="images/adcs-bottom.png" height="250"/>
</p>

### Physical Board
<p align="center">
  <img src="images/front and back adcs.jpeg" height="250"/>
</p>

### Routing Overview
<p align="center">
  <img src="images/adcs_routing.png" height="250"/>
</p>
