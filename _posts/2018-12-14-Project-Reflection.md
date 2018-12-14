---
layout: post
title: Bashir Hill, Project Reflection 
date: 2018-12-14 
---


   For my project I decided to make the pakistan flag I started by gthering the shapes needed to make the flag.As you can see from the code below I gathered the shapes neccesary to make the pakistan flag.I then used the place image function and started to put some of these shapes together   
                      



include image 

br = rectangle(100, 200, "solid", "blue")

rr = rectangle(300, 200, "solid", "red")

wr = rectangle(100, 200,  "solid", "white")

br-rr = place-image(br, 300 - 250, 200 - 100, rr) 


FranceFlag = place-image(wr, 300 - 150, 200 - 100, br-rr) 


wr2 = rectangle(20, 200,  "solid", "white")
wr3 = rectangle(400, 20,  "solid", "white")


w2-rr = place-image(wr2, 300 - 200, 200 - 100, rr) 

DenmarkFlag = place-image(wr3, 300 - 200, 200 - 100, w2-rr) 

