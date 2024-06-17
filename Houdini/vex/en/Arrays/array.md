---
title: array
order: 3
---
`<type>[] array(...)`

Returns an array of items of the given type.

You should use function-style casting to ensure the array members have the
correct type:

```vex
vector v[] = vector[](array( 1, {1,2,3}, 3, s, t, Cl, P, N));
float  f[] = float[](array(1, 2, s, t, length(P-L), length(N)));

```
