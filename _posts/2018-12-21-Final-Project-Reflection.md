---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of _Pakistan_ by _Bashir Hill_

## Describe your program
 

The flag I did was for  the country of Pakistan 

I think that I should get at least a practitioner because i made the flag correctly but i did not get all the dimensions correct


## Current output

 
* * *
![Flag](/images/final-flag.png)
* * *

## Describe your process.


I tackled what I knew how to do first then I asked my peers for help with the stuff that I couldnt figure out for myself or that I didnt understand It wasnt that hard to make my flag because I had done it in the past The most difficult part was rotating the star because I had forgotten about the command 


## Explain your code.


* * *

```
include image

height =  280
circle-radius = height * 3/10

#simpleparts

wr = rectangle(75, height,  "solid", "white")

gr = rectangle(300, 200, "solid", "dark-green" )

wc = circle(60, "solid", "white")

gc = circle(55, "solid", "dark-green")

ws = star(25,"solid", "white")

rws = rotate(26, ws)
```

* * *

 


This part of the code is important and it is labled simple parts because It was the parts that i needed to make the flag to put them all togehter I had to use the place image function to put them together to make the flag I defined them all as short abriviations of their names such as gr = green rectangle  wc = white circle etc the inlcude image function imports an image library that make the shapes apear when I program them in 
## Program code

```
include image

height =  280
circle-radius = height * 3/10

#simpleparts

wr = rectangle(75, height,  "solid", "white")

gr = rectangle(300, 200, "solid", "dark-green" )

wc = circle(60, "solid", "white")

gc = circle(55, "solid", "dark-green")

ws = star(25,"solid", "white")

rws = rotate(26, ws)
#combinationofsimpleparts

wr-gr = place-image(wr, 35, 75, gr)

ffc = place-image(wc, 185,100,wr-gr)

smg = place-image(gc,200,85,ffc)

pakistan-flag = place-image(rws,210,75,smg) 
```
