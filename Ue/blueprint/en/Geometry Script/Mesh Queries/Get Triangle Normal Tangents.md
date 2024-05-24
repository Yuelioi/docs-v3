---
display_name: Get Triangle Normal Tangents
order: 34
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Queries](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshQueries)

For the specified Triangle ID of the TargetMesh, get the Normal and Tangent vectors at each vertex of the Triangle.
These Normals/Tangents will be taken from the Normal and Tangents Overlays, i.e. they will potentially be split-normals.

Target is Geometry Script Library Mesh Query Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | Triangle ID |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Tri Has Valid Elements | will be returned true if TriangleID exists in TargetMesh and has Normals and Tangents set. |
| struct | Normals |  |
| struct | Tangents |  |
| struct | Bi Tangents |  |
| object | Target Mesh |  |
