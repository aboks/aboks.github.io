---
layout: talk
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

## Praise

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Fantastic talk by <a href="https://twitter.com/arnoutboks?ref_src=twsrc%5Etfw">@arnoutboks</a> at <a href="https://twitter.com/hashtag/phpday?src=hash&amp;ref_src=twsrc%5Etfw">#phpday</a> on how data (mis-)interpretation is at core in software design. <a href="https://t.co/asUJcwIOs7">pic.twitter.com/asUJcwIOs7</a></p>&mdash; Imported Domain Event (@Ocramius) <a href="https://twitter.com/Ocramius/status/1127162063871258624?ref_src=twsrc%5Etfw">May 11, 2019</a></blockquote>  

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">I deeply recommend this talk.<br><br>It&#39;s one of these talks that gives you that &quot;eureka&quot; feeling of better understanding several things with a higher level and more elegant explanation.<br><br>Great job <a href="https://twitter.com/arnoutboks?ref_src=twsrc%5Etfw">@arnoutboks</a> ! <a href="https://t.co/Cj61aO4E7p">https://t.co/Cj61aO4E7p</a></p>&mdash; Benoit Jacquemont (@BJacquemont) <a href="https://twitter.com/BJacquemont/status/1186181720879632385?ref_src=twsrc%5Etfw">October 21, 2019</a></blockquote> 

<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 