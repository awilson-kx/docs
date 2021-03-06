---
title: mod – Reference – kdb+ and q documentation
description: mod is a q keyword that returns the modulus of a number.
author: Stephen Taylor
keywords: kdb+, math, mathematics, modulus, q
---
# `mod`

_Modulus_



Syntax: `x mod y`, `mod[x;y]`

Where `x` and `y` are numeric, returns the remainder of `x%y`.
```q
q)-3 -2 -1 0 1 2 3 4 mod 3
0 1 2 0 1 2 0 1
```

`mod` is an atomic function.


## Domain and range

```txt
mod| b g x h i j e f c s p m d z n u v t
---| -----------------------------------
b  | i . i i i j e f . . p m d z n u v t
g  | . . . . . . . . . . . . . . . . . .
x  | i . i i i j e f . . p m d z n u v t
h  | i . i i i j e f . . p m d z n u v t
i  | i . i i i j e f . . p m d z n u v t
j  | j . j j j j e f . . p m d z n u v t
e  | f . f f f f f f f . f f z z f f f f
f  | f . f f f f f f f . f f z z f f f f
c  | . . . . . . . f . . p m d z n u v t
s  | . . . . . . . . . . . . . . . . . .
p  | n . n n n n n f n . . . . . . . . .
m  | i . i i i i i f i . . . . . . . . .
d  | i . i i i i i . i . . . . . . . . .
z  | f . f f f f f f f . . . . . . . . .
n  | n . n n n n n f n . . . . . . . . .
u  | u . u u u u u f u . . . . . . . . .
v  | v . v v v v v f v . . . . . . . . .
t  | t . t t t t t f t . . . . . . . . .
```

Range: `ijefpmdznuvt`

<i class="far fa-hand-point-right"></i> 
Basics: [Mathematics](../basics/math.md)