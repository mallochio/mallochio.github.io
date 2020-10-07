---
layout: post
title: Feature Showcase - Python 3.9
description: Examples of all the cool new features in python 3.9
comments: true
---

*Edit: Work in progress.*

---

Python 3.9 was released on the 6th of October, 2020. Along with that, a host of cool new features were released. 

###  1. Better math.gcd() and an additional math.lcm() function

Before 3.9 dropped, math.gcd only used to be able to handle pairs of digits. Now it can handle an arbitrary number of them. Let's take it for a spin, and calculate some GCDs and LCMs [^1].

``` python
>>> import math
>>> math.gcd(12,48,30)
# 6

>>> math.lcm(12,48,30)
# 240
```


---

Footnotes: 

[^1]: GCD stands for greatest common divisor while LCM stands for least common multiple. 

