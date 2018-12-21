---
layout: post
title: "Flag Project - Final Submission"
date: 2018-12-21
---

## Flag of _Pakistan_ by _Bashir Hill_

## Describe your program

-   What country did you design for? 
Pakistan 
-   What grade do you expect? 
At least a practitioner because i made th eflag correctly but i did not get all the dimensions correct
<!--- Delete this comment and add your writing -->

## Current output

-   Insert an image that your program currently produces. _then delete this instruction_

* * *
![Flag](/images/final-flag.png)
* * *

## Describe your process.

-   What questions, strategies, help from peers or teacher, or thinking got you to this point? _then delete this instruction_

<!--- Delete this comment and add your writing -->


## Explain your code.

-   Choose a significant part of your program (15 lines max) and paste it below. Do not insert your entire program here. _then delete this instruction_
-   Explain each argument in the code section. _then delete this instruction_
-   Tell us how it functions independently and within the whole program _then delete this instruction_

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

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.
 


This part of the code is important because 
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
