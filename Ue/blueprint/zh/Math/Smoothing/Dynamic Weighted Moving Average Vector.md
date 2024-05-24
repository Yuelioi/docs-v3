---
display_name: Dynamic Weighted Moving Average Vector
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Smoothing](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Smoothing)

Calculates the new value in a weighted moving average series using the previous value and a weight range.
The weight range is used to dynamically adjust based upon distance between the samples
This allows you to smooth a value more aggressively for small noise and let large movements be smoothed less (or vice versa)

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Current Sample | The value to blend with the previous sample to get a new weighted value |
| vector | Previous Sample | The last value from the series |
| real | Max Distance | Distance to use as the blend between min weight or max weight |
| real | Min Weight | The weight use when the distance is small |
| real | Max Weight | The weight use when the distance is large |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value | the next value in the series |
