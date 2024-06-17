---
title: solvecubic
order: 75
---
`int  solvecubic(float a, float b, float c, float d, float &t1, float &t2, float &t3)`

`int  solvecubic(float a, float b, float c, float d, vector2 &t1, vector2 &t2, vector2 &t3)`

Solves the given cubic function where a , b, c, and d are the coefficients as so: `ax^3 + bx^2 + cx + d = 0`

Returns the number of real roots.

In the real case the returned roots will be in ascending order. In case of only one root that root is filled into t1, t2, and t3.

In the complex case t1, t2, and t3 are the complex roots.
