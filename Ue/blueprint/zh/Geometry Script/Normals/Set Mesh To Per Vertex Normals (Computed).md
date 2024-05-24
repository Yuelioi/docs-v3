---
display_name: Set Mesh To Per Vertex Normals (Computed)
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Normals](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Normals)

Recompute the normals of TargetMesh by averaging the triangle/face normals around each vertex, using combined area and angle weighting.
Each vertex will have a single normal, ie there will be no hard edges.

Target is Geometry Script Library Mesh Normals Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Recompute the normals of TargetMesh by averaging the triangle/face normals around each vertex, using combined area and angle weighting.Each vertex will have a single normal, ie there will be no hard edges. |
