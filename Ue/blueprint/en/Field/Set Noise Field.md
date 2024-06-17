---
title: Set Noise Field
order: 21
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Field](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Field)

Defines a perlin noise scalar value if the sample is within a box

Target is Noise Field

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| real | Min Range | The initial function value between 0 and 1 will be scaled between MinRange and MaxRange before being multiplied by magnitude |
| real | Max Range | The initial function value between 0 and 1 will be scaled between MinRange and MaxRange before being multiplied by magnitude |
| transform | Noise Transform | Transform of the box in which the perlin noise will be defined |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value |  |
