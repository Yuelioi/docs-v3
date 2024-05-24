---
display_name: Get Interpolated Triangle UV
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Queries](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshQueries)

Compute the interpolated UV (A*UV1+ B*UV2+ C\*UV3), where (A,B,C)=BarycentricCoords and the UV positions are taken
from the specified TriangleID in the specified UVSet of the TargetMesh.

Target is Geometry Script Library Mesh Query Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | UV Channel |  |
| integer | Triangle ID |  |
| vector | Barycentric Coords |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Tri Has Valid UVs |  |
| vector2d struct | Interpolated UV |  |
| object | Target Mesh |  |
