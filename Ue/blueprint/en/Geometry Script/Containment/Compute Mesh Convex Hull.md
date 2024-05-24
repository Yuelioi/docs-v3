---
display_name: Compute Mesh Convex Hull
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Containment](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Containment)

Compute the Convex Hull of a given Mesh, or part of the mesh if an optional Selection is provided

Target is Geometry Script Library Containment Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| object | Hull Mesh |  |
| struct | Selection | selection of mesh faces/vertices to contain in the convex hull. If not provided, entire mesh is used. |
| struct | Options |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Hull Mesh |  |
| object | Target Mesh |  |
