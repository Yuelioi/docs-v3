---
display_name: Convert Spline to Polyline in Time Range
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Spline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Spline)

Given a threshold and start and end time range, returns a list of vertices along the spline that, treated as a list of segments (polyline), matches the spline shape in that range. Also fills a list of corresponding distances along the spline for each point.

Target is Spline Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| enum | Coordinate Space |  |
| real | Max Square Distance from Spline |  |
| real | Start Time Along Spline |  |
| real | End Time Along Spline |  |
| boolean | Use Constant Velocity |  |
| boolean | Allow Wrapping if Closed |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Out Points |  |
| real | Out Distances Along Spline |  |
| boolean | Return Value | Given a threshold and start and end time range, returns a list of vertices along the spline that, treated as a list of segments (polyline), matches the spline shape in that range. Also fills a list of corresponding distances along the spline for each point. |
