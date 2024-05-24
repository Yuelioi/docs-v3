---
display_name: Get Interpolated Triangle Vertex Color
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Queries](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshQueries)

Compute the interpolated Vertex Color (A*Color1 + B*Color2 + C\*Color3), where (A,B,C)=BarycentricCoords and the Colors are taken
from the specified TriangleID in the Vertex Color layer of the TargetMesh.

Target is Geometry Script Library Mesh Query Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | Triangle ID |  |
| vector | Barycentric Coords |  |
| linearcolor | Default Color |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Tri Has Valid Vertex Colors | will be returned true if TriangleID exists in TargetMesh and has Colors set, and otherwise will be returned false |
| linearcolor | Interpolated Color |  |
| object | Target Mesh |  |
