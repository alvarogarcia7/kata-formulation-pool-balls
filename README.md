# Pool Balls kata formulation

## Description

The pool ballks must be distributed in a very specific fashion, according to the rules.

The balls end up inside the triangle in a random order (depending on the previous match).

### A note about the problem domain

A triangle of pool balls is equivalent to an array of ball representations

<img src="./images/1.jpeg" width="400" height="400"><img src="./images/2.jpeg" width="400" height="400">
<img src="./images/3.jpeg" width="400" height="400"><img src="./images/4.jpeg" width="400" height="400">

In this case, a `String` is enough to represent it.

The valid format is:

  * Y for Yellow
  * B for Black
  * R for Red
  
## Input and output

Expected format:

```
amount:$AMOUNT
swap:$FROM,$TO
swap:$FROM,$TO
```

Example:

```
amount:2
swap:1,2
swap:1,8
```
  
## Problems

### Problem 1

Calculate **the minimum number** of necessary ball swaps from the initial state to the corect one

### Problem 2

Calculate **which ball swaps** are the minimum necessary set to arrange the balls. 

Suggestion: solve problem 1 first
