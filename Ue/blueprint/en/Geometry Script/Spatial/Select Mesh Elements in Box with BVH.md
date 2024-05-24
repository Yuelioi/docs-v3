---
display_name: Select Mesh Elements in Box with BVH
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Spatial](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Spatial)

Create Mesh Selection of mesh elements in TargetMesh contained by QueryBox, using QueryBVH to accellerate the computation.
Triangles are selected if MinNumTrianglePoints or more vertices are inside the box.
PolyGroups are selected if any of their triangles are inside the box

Target is Geometry Script Library Mesh Spatial

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Query BVH | is an acceleration structure previously built with TargetMesh. |
| struct | Query Box |  |
| struct | Options | control the fast winding number threshold |
| enum | Selection Type |  |
| integer | Min Num Triangle Points |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Selection |  |
| object | Target Mesh |  |
