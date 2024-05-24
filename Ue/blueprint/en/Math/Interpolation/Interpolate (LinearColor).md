---
display_name: Interpolate (LinearColor)
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Interpolation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Interpolation)

Interpolate Linear Color from Current to Target. Scaled by distance to Target, so it has a strong start speed and ease out.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| linearcolor | Current | Current Color |
| linearcolor | Target | Target Color |
| real | Delta Time | Time since last tick |
| real | Interp Speed | Interpolation speed, if the speed given is 0, then jump to the target. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| linearcolor | Return Value | New interpolated Color |
