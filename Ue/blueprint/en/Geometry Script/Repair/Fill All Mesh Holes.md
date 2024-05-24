---
display_name: Fill All Mesh Holes
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Repair](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Repair)

Tries to fill all open boundary loops (such as holes in the geometry surface) of a mesh.

Target is Geometry Script Library Mesh Repair Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Fill Options | specifies the method used to fill the holes. |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Num Filled Holes | reports the number of holes filled by the function. |
| integer | Num Failed Hole Fills |  |
| object | Target Mesh |  |
