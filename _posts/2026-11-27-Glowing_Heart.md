---
layout: post
title: PROJECT COLLECTION
subtitle: Project 1 glowing_heart
gh-repo: Wiz1702/Wiz1702.github.io
gh-badge: [star, fork, follow]
tags: [Me,Self]
comments: true
mathjax: true
author: Wisdom Akanwe
---

## Glowing Heart 

The first piece in my collection, *A Heart That Glows, Beats and Sings*, is the Glowing Heart. It uses four LEDs and a light sensor. The goal is for the LEDs to become brighter as the surroundings become darker and dimmer as the surroundings become brighter.

I wanted to make a soft heart that responds to its environment.

## Materials

- 1 LilyPad USB Plus
- 1 LilyPad light sensor
- 4 red sewable LEDs
- USB cable and power source
- Alligator clips for testing
- Conductive thread
- Felt for the heart
- Sewing needle and regular thread
- Scissors
- Computer with the Arduino IDE

## Revised Paper Prototype

My revised prototype shows the four LEDs arranged in two pairs. One pair connects to pin 6, and the other connects to pin 7. All four negative tabs connect to the LilyPad’s ground. The light sensor connects to positive power, ground, and A2 through its signal tab.

![Revised Glowing Heart paper prototype showing the LED pairs, light sensor, and LilyPad connections](/assets/img/glowing-heart.png)

## Alligator Prototype

I used alligator clips to test the connections before sewing the circuit onto the felt. This setup lets me check the sensor readings and LED behavior while the connections are easy to adjust.

![Glowing Heart circuit operating with alligator clips before sewing](/assets/img/alligator_clips.png)
![Glowing Heart circuit operating with alligator clips before sewing-dark room](/assets/img/alligator_clips_light.png)

## Working Piece

These photos show how the heart responds to two different lighting conditions.

**In darker surroundings**

The LEDs glow brightly.

![Completed Glowing Heart with bright LEDs in darker surroundings](/assets/img/glowing_heart_on.png)

**In brighter surroundings**

The LEDs are off as more light reaches the sensor.

![Completed Glowing Heart with dim LEDs in brighter surroundings](/assets/img/glowing_heart_off.png)

## Two Tips to My Past Self

1. **Check the light readings first.** Use the Serial Monitor to record readings in your actual bright and dark conditions. Use those values to set the brightness range in your program.
2. **Test before sewing.** Check each LED’s polarity and every connection with alligator clips. Keep separate conductive-thread paths from touching when you sew.

## Resources

- Professor Iris Howley’s COMP 103 class examples and *14_complexInputs.pdf* slides for reading analog sensors.
- Professor Iris Howley’s component handout for planning the paper prototype.
