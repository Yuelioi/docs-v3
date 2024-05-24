---
display_name: Auto Repair Normals
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Normals](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Normals)

Attempt to repair inconsistent normals in TargetMesh. Currently this is done in two passes. In the first pass, triangles with
reversed orientation from their neighours are incrementally flipped until each connected component has a consistent orientation,
if this is possible (note that this is not always globally possible, eg for a mobius-strip topology there is no consistent orientation).
In the second pass, the "global" orientation is detected by casting rays from outside the mesh. This may produce incorrect results for
meshes that are not closed.

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
| object | Target Mesh | Attempt to repair inconsistent normals in TargetMesh. Currently this is done in two passes. In the first pass, triangles withreversed orientation from their neighours are incrementally flipped until each connected component has a consistent orientation,if this is possible (note that this is not always globally possible, eg for a mobius-strip topology there is no consistent orientation).In the second pass, the "global" orientation is detected by casting rays from outside the mesh. This may produce incorrect results formeshes that are not closed. |
