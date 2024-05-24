---
display_name: Compute Mesh Local UVParam
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [UVs](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/UVs)

Compute local UV parameterization on TargetMesh vertices around the given CenterPoint / Triangle. This method
uses a Discrete Exponential Map parameterization, which unwraps the mesh locally based on geodesic distances and angles.
The CenterPoint will have UV value (0,0), and the computed vertex UVs will be such that Length(UV) == geodesic distance.

Target is Geometry Script Library Mesh UVFunctions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| vector | Center Point | the center point of the parameterization. This point must lie on the triangle specified by CenterPointTriangleID |
| integer | Center Point Triangle ID | the ID of the Triangle that contains CenterPoint |
| real | Radius | the parameterization will be computed out to this geodesic radius |
| boolean | Use Interpolated Normal | if true (default false), the normal frame used for the parameterization will be taken from the normal overlay, otherwise the CenterPointTriangleID normal will be used |
| vector | Tangent YDirection |  |
| real | UVRotation Deg |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Vertex IDs | output list of VertexIDs that UVs have been computed for, ie are within geodesic distance Radius from the CenterPoint |
| vector2d struct | Vertex UVs | output list of Vertex UVs that corresponds to VertexIDs |
| object | Target Mesh |  |
