---
display_name: Vector 2DInterp to Constant
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Interpolation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Interpolation)

Tries to reach Target at a constant rate.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector2d struct | Current | Actual position |
| vector2d struct | Target | Target position |
| real | Delta Time | Time since last tick |
| real | Interp Speed | Interpolation speed |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector2d struct | Return Value | New interpolated position |
