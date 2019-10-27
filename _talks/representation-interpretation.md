---
layout: default
title:  "Of representation and interpretation: A unified theory"
---

Many hard problems in programming originate from one single source: not properly distinguishing the representation
of data from the way it is interpreted. Have you ever written code that filters `$_GET` for SQL injection attempts?
Struggled with timezones? Tried to get escaping right for Javascript in HTML? Detected the character encoding of a
string? All are examples of this one problem.

In this talk we will look at some examples of the representation-interpretation problem and find the general pattern
behind it. We will see how primitive types make it so hard for us to get this right, and how we can use value objects
to steer us in the right direction. You’ll start finding many more examples of this pattern and understand them more
easily.

Contains: math, character sets, strong opinions on string escaping, and an almost illegal slide.