---
display_name: Derive Grid from Transform Bounds
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [WFCFunctions](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/WFCFunctions)

Derive grid from the bounds of an array of transforms
Assumptions:
-Transforms can only represent a single grid
-Sets empty starter option if there is a valid grid position with no transform
-Orientation is determined by the yaw of the first transform in the array

Target is Wave Function Collapse Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| transform | Transforms | Array of transforms (by ref) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
