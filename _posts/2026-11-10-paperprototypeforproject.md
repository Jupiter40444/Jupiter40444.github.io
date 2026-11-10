---
layout: post
title: We Didn't Start the Fire 
tags: [coding, light pins, final project, paper prototyping]
author: Jupiter Chapman
---
I have three separate wearable pieces for my final project - a belt, a t-shirt, and a felt necklace. The first two will require coding and some more complex circuitry with the t-shirt being the most complex, 
and the felt necklace will be relatively simple and powered by a battery holder. If the temperature sensor sewn onto my t-shirt detects a temperature greater than that of a burning building (or in reality slightly above
room temperature for demonstration purposes), then it will buzz morse code for SOS, play we didn't start the fire on a buzzer, and flash red lights. If the switch attached to the felt necklace is switched to "on" it will 
turn on several LED pins. 

![tshirt](https://jupiter40444.github.io/assets/img/tshirt.png)  
The t-shirt traces will likely be the most complicated aspect. There shouldn't be any problems with the conductive thread on the wrong side, but there will be some overlap going to the ground pin on the Arduino.
I'd like to try and insulate my thread with a shoelace, or try to use decorative embroidery to solve this problem. 

![belt](https://jupiter40444.github.io/assets/img/belt.png)   
The belt is a little bit simpler. It contains three snaps that will need to connect to the snaps on the t-shirt in order to give power to its circuit. The biggest problem that I foresee is working within such a small 
area. 

![necklace](https://jupiter40444.github.io/assets/img/necklace.png)   
The necklace is by far the easiest. I will sew from the positive battery holder pin to the switch, to the positive pin of the LED, to the negative pin of the following LED, and so on. Eventually this will loop back 
to the negative battery holder pin. 

