---
layout: default
img: MoveControl.png
alt: image-alt
project-date: Spring 2021
category: PCB Design
title: Motor Control Board
objective: To create a board to control up to 3 different DC motors with encoder feedback for use in a my universities entry in the NASA Mars Ice Challenge.
details: The board utilized the DRV8701 motor gate driver and an STM32 Microcontroller. Each motor driver uses 4 external mosfets for to create an H-Bridge circuit to allow for full speed control in both directions. Since these drivers would experience high torque loads, it needed to be able to handle high current, which is why the flexibility of a gate driver was desired. 
results: The board performed nominally in the final drill system and the team won second place in the competition overall.
---