---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of Pakistan by Derek Caminero

## Describe your program
I designed for the country Pakistan
I don't expect anything greater than a 3

## Current output

* * *
![Flag](/images/final-flag.png)
* * *

## Describe your process.
Just the learning of the function overlay-xy, and some help from some of my peers and teachers, i was able to finish the flag pretty quickly and be able to help some of my classmates if they needed help.

## Explain your code.
* * *
```
size = 100
width = size * 3
height = size * 2

WS = star(height / 9, "solid","white")
GP = rectangle(width,height,"solid","green")
WP = rectangle(width / 4,height,"solid","white")
wc = circle(height / 3,"solid","white")
WG = circle(height / 3.5,"solid","green")

flag1 = overlay-xy(WP,0,0,GP)
flag2 = overlay-xy(wc,-120,-35,flag1)
flag3 = overlay-xy(WG,-140,-30,flag2)
flag4 = overlay-xy(WS,-200,-40,flag3)
```
* * *
This code consists on overlay-xy which was the function that i was able to master even a little bit, so i could be able to have a white base, and then put on top of it a smaller rectangle that would represent the flag in a better way. I after putting the two bases i created a circle, which i put on top of the two rectangles so then i would put another circle and it looked like a semi moon. I finished the flag comepletly by putting a well measured star in the middle of the two circles that look like a semi moon. Even though there are many other ways to make a flag on pyret, i decided that overlay-xy was the best fiting one for my style. The only confusing part of overlay-xy would be that it only uses negative numbers since for some reason that is, where the program is.​
24
-   Choose a significant part of your program (15 lines max) and paste it below. Do not insert your entire program here. _then delete this instruction_
25
-   Explain each argument in the code section. _then delete this instruction_
26
-   Tell us how it functions independently and within the whole program _then delete this instruction_
27

 
## Program code

```
include image

size = 100
width = size * 3
height = size * 2

WS = star(height / 9, "solid","white")
GP = rectangle(width,height,"solid","green")
WP = rectangle(width / 4,height,"solid","white")
wc = circle(height / 3,"solid","white")
WG = circle(height / 3.5,"solid","green")

flag1 = overlay-xy(WP,0,0,GP)
flag2 = overlay-xy(wc,-120,-35,flag1)
flag3 = overlay-xy(WG,-140,-30,flag2)
flag4 = overlay-xy(WS,-200,-40,flag3)
```
