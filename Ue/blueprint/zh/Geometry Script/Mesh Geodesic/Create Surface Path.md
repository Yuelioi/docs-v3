---
display_name: Create Surface Path
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Geodesic](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshGeodesic)

Computes a PolyPath that represents a "straight" surface path starting at the prescribed point on the mesh, and continuing
in the indicated direction until reaching the requested path length or encountering a mesh boundary, whichever comes first.

Target is Geometry Script Library Mesh Geodesic Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh | defines the surface where the path is computed. |
| vector | Direction | is a three-dimensional vector that is projected onto the mesh surface to determine the path direction. |
| integer | Start Triangle ID | the ID of mesh Triangle that contains the start point of the path. |
| vector | Start Bary Coords | indicates the location of start point within the start triangle, in terms of barycentric coordinates. |
| real | Max Path Length | sets the maximal length of the path, but the actual path may be shorter as it automatically terminates when encountering a mesh boundary edge. |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Surface Path | holds on return a PolyPath that forms a "straight" path along the mesh surface from the start position. |
| boolean | Found Errors |  |
| object | Target Mesh |  |
