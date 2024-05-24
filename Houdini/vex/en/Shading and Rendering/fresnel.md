---
display_name: fresnel
order: 7
---
`void  fresnel(vector i, vector n, float eta, float &kr, float &kt)`

`void  fresnel(vector i, vector n, float eta, float &kr, float &kt, vector &R, vector &T)`

Computes the fresnel reflection/refraction contributions given an
incoming vector, surface normal (both normalized), and an index of
refraction (eta). The amount of reflected light will be returned in
kr, and the amount of transmitted light will be returned in kt.
Optionally, the reflection and transmission vectors can be returned in
the R and T variables. The R and <type> variables will be normalized
vectors on exit.

eta is a relative index of refraction, the ratio between
the interior and exterior index of refraction, where the exterior
is defined by the direction of the normals (normals point away from
the interior).
