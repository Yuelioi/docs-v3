---
display_name: henyeygreenstein
order: 13
---
`bsdf  henyeygreenstein(float anisotropic_bias, ...)`

The Henyey-Greenstein function scatters light either forward or in reverse depending on the `anisotropic_bias` provided to the function which must be a floating point value between -1 and 1. A value of 0 will cause isotropic scattering (identical to the `isotropic()` bsdf) while positive values produce forward scattering and negative values produce reverse scattering. The extrema of -1 and 1 cause all light to be scattered in a single direction, back toward the light for -1 and without any directional change for 1.

Note
No normal vector is required to construct a Henyey-Greenstein BSDF since it has no directionality. The default albedo for the BSDF is 1, which means it scatters 100% of the incoming light.
