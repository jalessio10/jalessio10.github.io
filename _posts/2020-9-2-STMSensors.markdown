---
layout: default
modal-id: 5
img: STMSensors.jpg
alt: image-alt
project-date: Summer 2020
category: C/C++ Programming
title: High-G Accelerometer and IMU Drivers
objective: To develop functional SPI drivers for the H3LIS331DL High-G accelerometer and LSM9DS1 IMU.
details: The drivers were written to be compiled in C (because it is more lightweight than C++) and tested on the STM32 platform using the STMCubeIDE. The sensor configuration and data are stored in structs using a similar scheme for both chips.
results: This was my first time writing sensor drivers and working at such a low level. I was able to first write an I2C driver for the High-G accelerometer. Once I was comfortable with my ability to work with I2C, I updated the driver for SPI and wrote the IMU driver for SPI. These drivers are currently deployed on the flight control boards the club is developing. They have also successfully been flown for data collection.
---