---
title: smooth
order: 15
---
`float  smooth(float value1, float value2, float amount)`

`float  smooth(float value1, float value2, float amount, float rolloff)`

Computes a number between zero and one. Returns 0 if the amount passed
in is less than or equal to value1, 1 if the amount is greater than or
equal to value2.

If the amount is between value1 and value2, a smooth (easin/easeout)
interpolation is computed. If a rolloff is specified, the inflection
point of the blend will be shifted.

If the rolloff is greater than 1, the shift will be to the right, if the
rolloff is less than 1 (and greater than 0), the shift will be to the
left.
