---
display_name: Clamp Angle
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Float](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Float)

Clamps an arbitrary angle to be between the given angles. Will clamp to nearest boundary.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| real | Angle Degrees |  |
| real | Min Angle Degrees | "from" angle that defines the beginning of the range of valid angles (sweeping clockwise) |
| real | Max Angle Degrees | "to" angle that defines the end of the range of valid angles |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | Returns clamped angle in the range -180..180. |
