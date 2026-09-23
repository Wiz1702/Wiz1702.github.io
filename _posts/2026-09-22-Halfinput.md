---
layout: post
title: LED TIME II
subtitle: Using the Switch and Button
gh-repo: Wiz1702/Wiz1702.github.io
gh-badge: [star, fork, follow]
tags: [Me,Self]
comments: true
mathjax: true
author: Wisdom Akanwe
---


{: .box-success}
I made my arduino LED lights blink, and I added a switch and a button.The goal was to simulate a button and a switch using variables and turn on different LEDs depending on their values.

**Code it**

So this time, we used the button(btn) and switch (swt) variables. We want to be able to turn an LED on when either of them is switched on!
Since we have not yet learned how to use the actual button and switch components, I represented them using Boolean variables.
To test my program, I changed the values of btn and swt and uploaded the code to the LilyPad USB Plus.

For example, when I set both variables to true, the LED on pin 5 turned on.
By changing the variables to different combinations, I could test the other LEDs.

**Using Nested over Logical Operators**
I used Nested Ifs in my code. I chose nested if statements because they allowed me to check btn first, followed by swt. 
This made my code easier to organize and understand, as I could clearly see how each combination of the two variables controlled a different LED.
I know the Logical operators would have made more sense to a beginner, but my code would be longer and not efficient when it gets to more complex codes.



## Tips
Listen in class, if you pay attention, most of these assignments should be pretty quick.



More to follow, stay tuned!!

