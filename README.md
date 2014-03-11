JustEat.Grad.RecruitmentTest
============================

Just Eat Grad Recruitment Test, thankyou for taking part !

### Requirements

Code your solution in any language you see fit but please give instructions on how to execute your code and see the output. <br />
Submit your solution as a zip file

This is a coding test, please read the requirements carefully and make sure your code is Object Oriented and easy to read.

### Scenario

Just-Eat wants you to help us with our research into Robotic takeaway delivery !
The experiment will take place in a very special simple place called takeawaytown, takeawaytown can be represented as an 8x8 Grid (each grid is a mile).
The Just-Eat delivery Robot (JEBot) needs some help with route finding to ensure that the nearest customer is delivered to first so their takeaway isn't cold,
JEBot can only move forward, back left and right (not diagonally).
Please devise a console application the does the following

1. Places two random delivery points in takeawaytown (represented with a 'D')
2. Places JEBot at a random location in takeawaytown (represented as 'JEB')
3. Draws TakeAwayTown clearly showing the delivery points and JEBot
4. Displays how many miles to the nearest Delivery point (remember JEBot cannot move diagonally).

```c#
|1,1|1,2|1,3|1,4|1,5|1,6|1,7|1,8|
|2,1|2,2|2,3|2,4|2,5|2,6|2,7|2,8|
|3,1|3,2|3,3|3,4|3,5|3,6|3,7|3,8|
|4,1|4,2|4,3|4,4|4,5|4,6|4,7|4,8|
|5,1|5,2|5,3|5,4|5,5|5,6|5,7|5,8|
|6,1| D |6,3| D |JEB|6,6|6,7|6,8|
|7,1|7,2|7,3|7,4|7,5|7,6|7,7|7,8|
|8,1|8,2|8,3|8,4|8,5|8,6|8,7|8,8|

Shortest Delivery Point: 1 Mile - 6, 4
```

Post Questions:
1. If takeawaytown was a much much larger size would you have used a different data structure ? if so what and why ?
