---
display_name: Apply Simplify to Planar
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Simplification](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Simplification)

Simplifies planar areas of the mesh that have more triangles than necessary. Note that it does not change the 3D shape of the mesh.
Planar regions are identified by comparison of face normals using a Angle Threshold in the Options.

Target is Geometry Script Library Mesh Simplify Functions

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
| object | Target Mesh | Simplifies planar areas of the mesh that have more triangles than necessary. Note that it does not change the 3D shape of the mesh.Planar regions are identified by comparison of face normals using a Angle Threshold in the Options. |
