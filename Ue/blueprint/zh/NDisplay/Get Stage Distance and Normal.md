---
display_name: Get Stage Distance and Normal
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [NDisplay](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/NDisplay)

Gets the distance and normal vector (in radial space) of the stage's geometry in the specified world direction

Target is Display Cluster Stage Geometry Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | In Direction | The direction in world coordinates to query the stage geometry map |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Out Distance | The distance from the stage's default view origin to the nearest stage geometry in the specified direction |
| vector | Out Normal | The normal vector in radial space (with x axis pointing in the direction of the stage's default view origin) of the nearest stage geometry in the specified direction |
| boolean | Return Value | true if the stage geometry map was successfully queried, otherwise false |
