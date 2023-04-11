---
layout: post
title: Ghost Detector
subtitle: Assignment due Apr. 12
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [Assignment]
thumbnail-img: /assets/img/gfish.jpg
comments: true
---
**Description of Assignment**: We wrote an arduino program that lights up all red LEDs on the Arduino board when it is dark and cold enough. Instead of setting
a specific value for the two thresholds, I made the thresholds be whatever the bottom 25% value the sensor gave between the max and min values. Unnecessary for
this assignment yes, but it was just an attempt to make the code more useful when testing in different environments.
  
![ghostDetector](https://darrendywang.github.io/assets/img/ghostDetector.jpg)  


**Tip**: The problem about initializing a lot of variables at the top is that mistypes happen. My temp sensor didn't work on the first try, which was surprising since
I had just copied the light sensing code. Turns out I forgot that I had left tempVal in the code, even though the first thing we did was to convert it to a different
unit. So my tip is just to read carefully the code after copy and pasting since variable names can be tricky.
