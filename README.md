# Pool Balls kata formulation

## Description

The pool ballks must be distributed in a very specific fashion, according to the rules.

The balls end up inside the triangle in a random order (depending on the previous match).

### Problem 1

Calculate how many ball swaps are necessary to arrange the balls from the initial state to the corect one

Expected format:

```
amount:$AMOUNT
```

Example:

```
amount:0
```

### Problem 2

Calculate which ball swaps are necessary to arrange the balls. 

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

Suggestion: solve problem 1 first

