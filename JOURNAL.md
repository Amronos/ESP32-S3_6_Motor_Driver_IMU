---
title: "ESP32-S3 6 Motor Driver with IMU"
author: "Aarav Gupta"
description: "A board featuring an ESP32-S3, a 6-channel DC motor driver, an integrated IMU, and support for encoder feedback."
created_at: "2025-06-17"
total_time_spent: 29.5 hours
---

## 24th June 2025: Started Working on Library

I started working on the Arduino library for the board today. It is/will be a wrapper around other libraries that are used to control the BNO086 and DRV8912-Q1.<br>
Today I created functions in the library for easily getting data from the IMU and printing it alongside an example Arduino sketch.<br>
I am using the [SparkFun BNO08x Cortex Based IMU Library](https://github.com/sparkfun/SparkFun_BNO08x_Arduino_Library) for the BNO086 and will creating my own library for the DRV8912-Q1.

**Total time spent: 4h**

## 23rd June 2025: Created BOM

Today I created the almost final BOM for the board containing all the components used on the board.

**Total time spent: 3h**

## 19th to 22nd June 2025: Completed PCB

I spent these 4 days creating the PCB layout and routing all the tracks. I also added test points and LEDs, alongisde fixing the last few errors with the schematic.

| ![Top Layer of PCB](assets/journal/06-22_1.png) |
| :---------------------------------------------: |
|                Top Layer of PCB                 |

**Total time spent: 15h**

## 18th June 2025: Created a Diagram Showing ROS 2 Usage

Today I created a diagram showing how the board will be used with ROS 2, this will be useful to create the ROS 2 code to be used with this board.
I also made some fixes to the schematic.

| ![ROS 2 Usage Diagram](code/ros2/ROS2_Usage.drawio.svg) |
| :-----------------------------------------------------: |
|                   ROS 2 Usage Diagram                   |

**Total time spent: 1.5h**

## 17th June 2025: Created Board Schematic

Today I created the full schematic for the board.
I settled on the following ICs: ESP32-S3, BNO086(IMU), DRV8912-Q1(Motor Driver), LMR38020FDDAR(5V Regulator), TPS2116DRLR(Power Mux for selecting between 5V from regulator and USB), LD39200PU33R(3.3V Regulator).

| ![Schematic](assets/journal/06-17_1.svg) |
| :--------------------------------------: |
|                Schematic                 |

**Total time spent: 6h**
