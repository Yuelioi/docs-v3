---
title: solvequadratic
order: 77
---
`int  solvequadratic(float a, float b, float c, float &t1, float &t2)`

`int  solvequadratic(float a, float b, float c, vector2 &t1, vector2 &t2)`

Solves the given quadratic function where a , b, and c are the coefficients as so: `ax^2 + bx + c = 0`.

Returns the number of real roots.

In the real case t1 and t2 are filled such that t1 ≤ t2. If there is only one root then t1 = t2. If there are no roots then t1 = t2 and is the projection of the vertex of the quadratic function onto the x-axis.

In the complex case t1 and t2 are the complex roots.
