---
display_name: Remove Hidden Triangles
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Repair](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Repair)

Removes any triangles in the mesh that are not visible from the exterior view, under various definitions of "visible" and "outside"
as specified by the Options.

Target is Geometry Script Library Mesh Repair Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Options |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Removes any triangles in the mesh that are not visible from the exterior view, under various definitions of "visible" and "outside"as specified by the Options. |
