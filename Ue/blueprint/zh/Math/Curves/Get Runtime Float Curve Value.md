---
title: Get Runtime Float Curve Value
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Curves](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Curves)

Evaluate this runtime float curve at the specified time

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Curve | The runtime float curve to evaluate |
| real | In Time | The time at which to evaluate the curve |
| real | In Default Value | The default value which should be used if the curve cannot be evaluated at the given time. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | The curve's value at the given time. |
