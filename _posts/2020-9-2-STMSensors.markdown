---
layout: default
img: STMSensors.jpg
alt: image-alt
project-date: Summer 2020
category: C/C++ Programming
title: High-G Accelerometer and IMU Drivers
objective: To develop functional SPI drivers for the H3LIS331DL High-G accelerometer and LSM9DS1 IMU.
details: The drivers are written in C (because it is more lightweight than C++) and tested on the STM32 platform using the STMCubeIDE. The sensor configuration and data is stored in structs using a similar scheme for both chips.
results: This was my first time writing sensor drivers and working at such a low level. I was able to first write a I2C driver for the High-G accelerometer. Once I was comfortable with my ability to work with I2C, I updated the driver for SPI and wrote the IMU driver for SPI. These drivers are currently deployed on the FCB’s the club is developing and have been used to collect data from several flights.
---