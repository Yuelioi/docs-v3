---
display_name: Weighted Moving Average Vector
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Smoothing](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Smoothing)

Calculates the new value in a weighted moving average series using the previous value and the weight

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Current Sample | The value to blend with the previous sample to get a new weighted value |
| vector | Previous Sample | The last value from the series |
| real | Weight | The weight to blend with |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value | the next value in the series |
