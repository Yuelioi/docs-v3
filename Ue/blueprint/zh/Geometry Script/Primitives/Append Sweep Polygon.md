---
display_name: Append Sweep Polygon
order: 22
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Primitives](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Primitives)

Sweep the given 2D PolygonVertices along the SweepPath specified as a set of FTransforms
If the 2D vertices are (U,V), then in the coordinate space of the FTransform, X points "along" the path,
Y points "right" (U) and Z points "up" (V).

Target is Geometry Script Library Mesh Primitive Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Primitive Options |  |
| transform | Transform |  |
| vector2d struct | Polygon Vertices | vertices of the closed 2D polyon that will be swept along the SweepPath |
| transform | Sweep Path | defines the 3D sweep path curve as a 3D poly-path, with rotation and scaling at each polypath vertex taken from the Transform |
| boolean | Loop | if true, SweepPath is considered to be a Loop and a section connecting the end and start of the path is added (bCapped is ignored) |
| boolean | Capped | if true the open ends of the swept generalized cylinder are triangulated |
| real | Start Scale | uniform scaling applied to the 2D polygon at the start of the path. Interpolated via arc length to EndScale at the end of the path. |
| real | End Scale | uniform scaling applied to the 2D polygon at the end of the path |
| real | Rotation Angle Deg | Rotation applied to the 2D Polygon. Positive rotation rotates clockwise, ie Up/+Z/+V towards Right/+Y/+U |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh |  |
