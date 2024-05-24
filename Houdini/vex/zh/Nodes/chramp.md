---
display_name: chramp
order: 14
---
`float  chramp(string channel, float ramppos)`

`float  chramp(string channel, float ramppos, float time)`

`vector  chramp(string channel, float ramppos)`

`vector  chramp(string channel, float ramppos, float time)`

Evaluates a ramp parameter and return its value.

The ramppos is where on the ramp to evaluate. The ramppos is clamped to the range `[0,1]`.

The time parameter can be used if the ramp is animated to evaluate
at other than the current time.
