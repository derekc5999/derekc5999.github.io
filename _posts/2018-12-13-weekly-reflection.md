---
layout: post
title: "Flag Project-In Process"
date: 2018-12-13
---
On this past few days, we came back to the flag project, so we could make the real deal! I made the flag of Pakistan on pyret and here is the code that i used, and some difficulties i had:

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
