---
display_name: Get Triangle Indices
order: 33
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Queries](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshQueries)

Returns the Vertex ID triplet for the specified Triangle.

Target is Geometry Script Library Mesh Query Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target Mesh |  |
| integer | Triangle ID | indicates the triangle to query on the Target Mesh. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Is Valid Triangle | will be false on return if the Triangle ID does not exist in the Target Mesh, in that case the returned vertex triplet will be (-1, -1, -1). |
| struct | Indices |  |
