---
title: Convert Spline to Poly Line
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Spline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Spline)

Given a threshold, returns a list of vertices along the spline that, treated as a list of segments (polyline), matches the spline shape.

Target is Spline Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| enum | Coordinate Space |  |
| real | Max Square Distance from Spline |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Out Points |  |
| boolean | Return Value | Given a threshold, returns a list of vertices along the spline that, treated as a list of segments (polyline), matches the spline shape. |
