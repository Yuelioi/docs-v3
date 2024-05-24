---
display_name: Divide Spline Into Polyline Recursive with Distances
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Spline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Spline)

Given a threshold, recursively sub-divides the spline section until the list of segments (polyline) matches the spline shape. Note: Prefer ConvertSplineToPolyline_InDistanceRange

Target is Spline Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| real | Start Distance Along Spline |  |
| real | End Distance Along Spline |  |
| enum | Coordinate Space |  |
| real | Max Square Distance from Spline |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Out Points |  |
| real | Out Distances Along Spline |  |
| boolean | Return Value | Given a threshold, recursively sub-divides the spline section until the list of segments (polyline) matches the spline shape. Note: Prefer ConvertSplineToPolyline_InDistanceRange |
