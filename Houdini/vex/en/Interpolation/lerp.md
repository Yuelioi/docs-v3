---
title: lerp
order: 10
---
`float  lerp(float value1, float value2, float amount)`

Performs linear interpolation between the values.

`<vector> lerp(<vector>value1, <vector>value2, float amount)`

Performs linear interpolation between corresponding components.

`<vector> lerp(<vector>value1, <vector>value2, <vector>amount)`

Performs linear interpolation between corresponding components by specific amounts for each component pair.

`bsdf  lerp(bsdf bsdf1, bsdf bsdf2, float amount)`

Returns a BSDF that linearly interpolates between the output of the two given BSDFS.

Show/hide arguments

`amount`

If the amount is outside the range 0 to 1, the values will be extrapolated linearly.

If amount is 0, the first value is returned. If it is 1, the second value is returned.
