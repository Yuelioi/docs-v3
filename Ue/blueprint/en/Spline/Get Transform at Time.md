---
display_name: Get Transform at Time
order: 71
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Spline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Spline)

Given a time from 0 to the spline duration, return the spline's transform at the corresponding position.

Target is Spline Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| real | Time |  |
| enum | Coordinate Space |  |
| boolean | Use Constant Velocity |  |
| boolean | Use Scale |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Return Value | Given a time from 0 to the spline duration, return the spline's transform at the corresponding position. |
