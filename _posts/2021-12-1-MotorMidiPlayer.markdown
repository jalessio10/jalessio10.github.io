---
layout: default
modal-id: 12
img: Motor.png
alt: image-alt
project-date: Fall 2021
category: Python Programming
title: Stepper Motor Midi Player
objective: To play music using the stepper motors without having to program each specific song.
details: Stepper motors with Trinamic motor drivers were used because Trinamic maintains a Python module for controlling them and I happened to be using them already at work. I decided to make my player use midi files, because there are many that can be downloaded freely online anad it is easy to write music and export it in midi format. The configuration data for the motors was stored in a json file, which can be easily parsed by the program.
results: I tested the player with two stepper motors playing seperate parts and it proved functional. By turning down the microstep resolution it was able to play surprisingly loudly, and all the notes played through perfectly in tune.
---