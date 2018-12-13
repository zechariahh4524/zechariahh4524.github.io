---
layout: post
title: "Flag project- in process"
date: 2018-12-13
---
hello everyone it's time not for a weekly reflection but my process on making the Flag of puerto rico first some questions i had.I at first didn't know exaclty how to take the basic shape and make a flag so my first question was how do i overlay shapes after i figured that out the next question i had was how to rotate a rectangle for strips i in the end i just changed the width and height to get the shape i needed but then i learned to rotate a triangle for my flag after i figured that out i could finish my flag and i did all around this was i good project that gave me the opportunite to make a flag for the first time and that all i have to say of now until next time i'm looking forward to what next
include image

size = 100
width = size * 3
height = size * 2

Rr = rectangle(350,200,"solid","red")
Sw = star(height / 5, "solid","white")
Rw = rectangle(350,40, "solid","white")
Tb = triangle(200, "solid","blue")
Rw2 = rectangle(350,40, "solid","white")
RTb = rotate(30, Tb)

flag1 = overlay-xy(Rw,0,-120,Rr)
flag2 = overlay-xy(Rw2,0,-40,flag1)
flag3 = overlay-xy(RTb,0,0,flag2)
flag4 = overlay-xy(Sw,-20,-60,flag3)
