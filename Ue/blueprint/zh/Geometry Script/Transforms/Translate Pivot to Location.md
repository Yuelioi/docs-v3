---
display_name: Translate Pivot to Location
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Transforms](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Transforms)

Set the Pivot Location for the Mesh. Since the Pivot of a Mesh object is always the point at (0,0,0),
this function simply translates the mesh by -PivotLocation.

Target is Geometry Script Library Mesh Transform Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| vector | Pivot Location |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Set the Pivot Location for the Mesh. Since the Pivot of a Mesh object is always the point at (0,0,0),this function simply translates the mesh by -PivotLocation. |
