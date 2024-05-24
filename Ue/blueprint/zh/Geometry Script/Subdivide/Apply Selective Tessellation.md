---
display_name: Apply Selective Tessellation
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Subdivide](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Subdivide)

Selectively Tessellate a Selection of the Target Mesh or possibly the entire mesh as controlled by
the Options.

Target is Geometry Script Library Mesh Subdivide Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Selection | selects the triangles of the mesh to be tessellated. |
| struct | Options | controls the behavior of the tessellation if the Selection is empty. |
| integer | Tessellation Level | determines the amount of tessellation |
| enum | Pattern Type |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh |  |
