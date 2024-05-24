---
display_name: Line Trace Tracked Objects 3D
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AR Augmented Reality](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality) > [Trace Result](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality/TraceResult)

Perform a line trace against any real-world geometry as tracked by the AR system.

Target is ARBlueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Start | Start point of the trace, in world space. |
| vector | End | End point of the trace, in world space. |
| boolean | Test Feature Points |  |
| boolean | Test Ground Plane |  |
| boolean | Test Plane Extents |  |
| boolean | Test Plane Boundary Polygon |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | a list of \\c FARTraceResult sorted by distance from camera. |
