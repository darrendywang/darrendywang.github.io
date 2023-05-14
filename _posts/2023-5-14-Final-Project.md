---
layout: post
title: Nap Mask Project Report
subtitle: Assignment due May 17
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [Assignment]
thumbnail-img: /assets/img/gfish.jpg
comments: true
---
**Project Motivation**: My sleep quality is highly determined by light: it's hard to fall asleep with it, and hard to wake up without it.
As someone who likes to wake up early, I often take short afternoon naps, but I often find it hard to fall asleep due to the bright afternoon
sun. However, a sleep mask isn't ideal since it lets in no light and therefore I wake up feeling horrible. I wanted a sleep mask that eases
me awake from a nap with light. This is a real product, but I can't afford it so I shall make my one.  

**Project Description**: This sleep mask's alarm can be set by the user. The program turns on in a "press any button to start" mode, and after
the button is pressed the user has 5 seconds to press the button however many times, with each click adding 5 minutes to the timer. After this,
the on-board LEDs confirm the user input by flashing the red LED once for every 10 minutes and the green LED once for every 5 minutes. If the timer
is correct, it starts counting down. 3 minutes before it goes off, LEDs near (not on) the eye area turns on at a low brightness that increases until
it hits the max when the timer is up, during which the lights flash and an alarm sound goes off. The alarm will only go off it the mask is on
someone's face, determined by a temperature sensor.  

**Material List**:  
1x cloth face mask  
1x sheet of felt about 16x10cm  
1x LilyPad Arduino  
1x LilyPad Arduino battery  
1x buzzer
1x temperature sensor  
2x white LEDs  
1x button  
conductive thread  
embroidery threat  

**Paper Prototype**  
![FinProjPapProt](https://darrendywang.github.io/assets/img/FinProjPapProt.jpg)  

**Alligator Prototype**  
![AlligatorProt](https://darrendywang.github.io/assets/img/FinalAlligator.JPG)  

**Working Project (Rest)**  
![FInalProjectRest](https://darrendywang.github.io/assets/img/Final1.JPG)  

**Working Project (Press Any Button)**  
![FInalProjectPressAnyButton](https://darrendywang.github.io/assets/img/Final2.JPG)  

**Working Project (Alarm Set)**  
![FInalProjectAlarmSet](https://darrendywang.github.io/assets/img/Final3.JPG)  

**Working Project (LED on)**  
![FInalProjectLedOn](https://darrendywang.github.io/assets/img/Final4.JPG)  

**Tips to Past Self**  
1. Fitting a flat (2D) surface over a curved (3D) surface was much harder than I expected. I should have gone to fab lab to borrow a bunch of safety pins to first "stitch" the felt onto the mask to match the fit rather than guessing. Guessing led to some asymmetry that doesn't look as good.
2. Don't try to secure components to the felt with just conductive wire. I should have glued them on first or something. All of the contacts are good except for one side of the button, which can be a bit annoying since the program doesn't register clicks perfectly.
3. For the coding part, breaking every action into functions and writing separate functions was a great decision. This modular style of coding made it a breeze and I finished (from start to finish) the entire code in <1.5 hours.








