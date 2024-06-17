---
title: slerp
order: 13
---
`vector4  slerp(vector4 q1, vector4 q2, float bias)`

Blends between quaternions q1 and q2 based on the bias.

`vector4  slerp(vector4 qs[], float weights[], int normalize=0)`

Blends between any number of quaternions with the specified corresponding weights. `slerp(q1,q2,bias)` is equivalent to `slerp(array(q1,q2), array(1.0-bias,bias))`.

By default, the weights are assumed to be normalized. If this is not the case, pass 1 for the normalize parameter to normalize them prior to interpolation or else undefined results will be returned.

`matrix3  slerp(matrix3 m1, matrix3 m2, float bias)`

`matrix  slerp(matrix m1, matrix m2, float bias)`

Blends between matrix m1 and m2 based on the bias.

`matrix3  slerp(matrix3 ms[], float weights[], int normalize=1)`

`matrix  slerp(matrix ms[], float weights[], int normalize=1)`

Blends between any number of matrices with the specified corresponding weights via blending of their components via polar decomposition.

By default, the weights are normalized before blending. If the weights are already normalized, you can pass 0 for the normalize parameter.
