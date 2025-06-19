---
title: "ESP32-S3 6 Motor Driver with IMU"
author: "Aarav Gupta"
description: "A board featuring an ESP32-S3, a 6-channel DC motor driver, an integrated IMU, and support for encoder feedback."
created_at: "2025-06-17"
total_time_spent: 7.5 hours
---

## 17th June 2025: Created Board Schematic

Today I created the full schematic for the board.
I settled on the following ICs: ESP32-S3, BNO086(IMU), DRV8912-Q1(Motor Driver), LMR38020FDDAR(5V Regulator), TPS2116DRLR(Power Mux for selecting between 5V from regulator and USB), LD39200PU33R(3.3V Regulator).

| ![Schematic](hardware_design/schematic.svg) |
| :-----------------------------------------: |
|                  Schematic                  |

**Total time spent: 6h**

## 18th June 2025: Created a Diagram Showing ROS 2 Usage

Today I created a diagram showing how the board will be used with ROS 2, this will be useful to create the ROS 2 code to be used with this board.
I also made some fixes to the schematic.

| ![ROS 2 Usage Diagram](code/ros2/ROS2_Usage.drawio.svg) |
| :-----------------------------------------------------: |
|                   ROS 2 Usage Diagram                   |

**Total time spent: 1.5h**
