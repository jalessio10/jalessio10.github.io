---
layout: default
modal-id: 3
img: DeploymentInterface.jpg
alt: image-alt
project-date: Fall 2019
category: PCB Design
title: Mechanical Deployment Interface
objective: To create a PCB that would enable servo control with proven off-the-shelf dual deployment altimeters. I designed the PCB using a previously tested perfboard prototype built by previous club members as reference.
details: We chose to design a board to adapt flight-proven, off-the-shelf altimeters (designed to deploy parachutes using electronic matches) to control servos. This board was necessary for the club to develop mechanical deployment mechanisms that did not rely on lighting black powder charges. We decided to use an RC circuit to read the voltage from the e-match output on the commercial altimeter. Further, I used an ATmega328P with the Arduino bootloader to control the servo motors.
results: The first version of this board was reworked to add more protection because inrush from plugging in the batteries killed the voltage regulators. The board was flown in this configuration and performed nominally. A new version was designed that fixed this issue but was never flown due to traveling restraints with COVID-19. The club has since built its own altimeters and is developing and testing its own flight control algorithms.
---