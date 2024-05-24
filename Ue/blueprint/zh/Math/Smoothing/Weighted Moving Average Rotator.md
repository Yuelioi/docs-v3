---
display_name: Weighted Moving Average Rotator
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Smoothing](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Smoothing)

Calculates the new value in a weighted moving average series using the previous value and the weight

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| rotator | Current Sample | The value to blend with the previous sample to get a new weighted value |
| rotator | Previous Sample | The last value from the series |
| real | Weight | The weight to blend with |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| rotator | Return Value | the next value in the series |
