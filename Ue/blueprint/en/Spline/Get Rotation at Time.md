---
title: Get Rotation at Time
order: 55
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Spline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Spline)

Given a time from 0 to the spline duration, return a rotation corresponding to the spline's position and direction there.

Target is Spline Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| real | Time |  |
| enum | Coordinate Space |  |
| boolean | Use Constant Velocity |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| rotator | Return Value | Given a time from 0 to the spline duration, return a rotation corresponding to the spline's position and direction there. |
