---
display_name: Get Triangle Positions
order: 36
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Queries](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshQueries)

- Returns the 3D positions (in the mesh local space) of the three vertices of the requested triangle.
- If the Triangle ID is not an element of the Target Mesh, all three vertices will be returned as (0, 0, 0) and bIsValidTriangle will be set to false.

Target is Geometry Script Library Mesh Query Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target Mesh |  |
| integer | Triangle ID |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Is Valid Triangle |  |
| vector | Vertex 1 |  |
| vector | Vertex 2 |  |
| vector | Vertex 3 |  |
