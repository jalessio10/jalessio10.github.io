---
layout: default
modal-id: 12
img: Motor.png
alt: image-alt
project-date: Fall 2021
category: Python Programming
title: Stepper Motor Midi Player
objective: To play music using the stepper motors without needing to program each specific song.
details: I used stepper motors with Trinamic motor drivers because Trinamic maintains a Python module for controlling them; I also happened to be using them already at work. I decided to make my player use midi files because many are freely available online. Further, it is easy to write music and export it in midi format. The configuration data for the motors were stored in a JSON file for easy parsing.
results: I successfully tested the player with two stepper motors playing separate parts. With a low micro-step resolution the motors played surprisingly loudly. In addition, due to the nature of stepper motors, all the notes played perfectly in tune.
---