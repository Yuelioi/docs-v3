---
title: sample_exponential
order: 16
---
`float  sample_exponential(float u)`

`float  sample_exponential(float mean, float u)`

`float  sample_exponential(float origmean, float maxvalue, float u)`

Show/hide arguments

`u`

A number in the range `[0,1)`.

`mean`

The mean of the distribution, or 1 if not specified.

`origmean`

The mean the distribution would have, were it not for `maxvalue`,
limiting the range.

`maxvalue`

When given, instead of sampling the full exponential distribution,
the distribution with its range limited to `[0,maxvalue]` will be
sampled.

Samples the exponential distribution with the specified `mean`, optionally
with a `maxvalue`.
Given uniform random `u` values in `[0,1)`, this will return exponentially
distributed random numbers. The return value will be monotone increasing
with respect to `u`.
