---
display_name: Select Mesh Elements in Box
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Selection](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshSelection)

Create a new Mesh Selection of the SelectionType for the TargetMesh by finding all elements contained in the Box.

Target is Geometry Script Library Mesh Selection Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Box |  |
| enum | Selection Type |  |
| boolean | Invert | return a selection of all elements not in the Box |
| integer | Min Num Triangle Points | number of vertices of a triangle that must be in the box for it to be selected (1,2, or 3) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Selection |  |
| object | Target Mesh |  |
