---
display_name: ConvertComponentsToPolyGroups
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Poly Groups](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PolyGroups)

Creates and assigns a new PolyGroup for each disconnected component of a Mesh. Regions of a mesh are disconnected they do not have a triangle in common.
Note, this will have no effect if the Group Layer does not exist.

Target is Geometry Script Library Mesh Polygroup Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Group Layer |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Creates and assigns a new PolyGroup for each disconnected component of a Mesh. Regions of a mesh are disconnected they do not have a triangle in common.Note, this will have no effect if the Group Layer does not exist. |
