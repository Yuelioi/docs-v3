---
display_name: sample_hemisphere
order: 18
---
`vector  sample_hemisphere(vector2 u)`

`vector  sample_hemisphere(vector center, vector2 u)`

`vector  sample_hemisphere(float bias, vector2 u)`

`vector  sample_hemisphere(vector center, float bias, vector2 u)`

Show/hide arguments

`center`

Direction in the center of the hemisphere. This does not need to be normalized.
If not specified, the center direction is (1,0,0), along the x-axis.

`bias`

Bias toward the center direction, between -1 and infinity, with 0 being unbiased,
-1 forcing all points to the horizon, and infinity forcing all points to center.
When supplied, `u.y` is simply replaced with `1-pow(1-u.y, 1.0/(bias+1.0))`. To
get a bias similar to this when using the more general `sample_direction_cone`,
`sample_sphere_cone`, and related functions, apply the same change to `u.x`
before calling those functions.

`u`

Pair of numbers between 0 and 1.

Returns a unit vector, i.e. a vector of length 1, based on `u`.
Given uniform random `u` pairs of values in `[0,1)`, if `bias` is 0, the
returned unit vectors will be uniform random and continuous with respect to
`u` on the surface of the unit hemisphere centered at `center`. If bias is
greater than zero, the unit vectors will be smoothly biased toward `center`.
If bias is between -1 and 0, the unit vectors will be biased away from
`center`, toward the horizon.
