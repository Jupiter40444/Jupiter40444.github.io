---
layout: post
title: Ghost Detector Coding Project 
tags: [sensors, light pins, coding]
author: Jupiter Chapman
---
For this project I coded a simple program that would turn on the red pin in the center of the arduino, the light pin still attratched to the board, and the off board RGB pin we were given last week. If the 
light sensor was low enough (ie. I put my hand over it) and the temperature sensor was cold enough (ie. we were in a normal room with a normal temperature), the lights would turn on. I decided to test this with 
real numbers inside of the code, however I could've also used stored variables, like lightThreshold or tempThreshold. It was pretty difficult to get the RGB offboard pin to work, since I was already connecting the 
offboard temperature sensor. If I could give a tip to my past self it would be to simplify the code given to us on the moodle before pasting it into the arduino file, as some of it wasn't necessary for this particular problem. 

![ghostdetect](https://jupiter40444.github.io/assets/img/ghostdetect.png)  

