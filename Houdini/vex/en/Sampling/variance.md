---
display_name: variance
order: 32
---
`float  variance(float variable, float &mean, int &sample_size)`

This function will compute the mean and variance from nearby samples. Similar to the way that VEX is able to compute derivatives, this function is able to inspect the `variable` for a nearby area and compute the mean and variance of the `variable`.

The function returns the `variance` (σ2). The `mean` value will also be returned along with the `sample_size` indicating how many nearby samples were considered.
