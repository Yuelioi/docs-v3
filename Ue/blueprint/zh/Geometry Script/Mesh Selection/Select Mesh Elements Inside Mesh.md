---
title: Select Mesh Elements Inside Mesh
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Selection](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshSelection)

Create a new Mesh Selection of the SelectionType for the TargetMesh by finding all elements inside a second SelectionMesh
For Triangle and PolyGroup selections the triangle facet normal is used, for Vertex selections the per-vertex averaged normal is used.

Target is Geometry Script Library Mesh Selection Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| object | Selection Mesh |  |
| transform | Selection Mesh Transform | Transform applied to SelectionMesh for inside/outside testing |
| enum | Selection Type |  |
| boolean | Invert | return a selection of all elements not within the given deviation |
| real | Shell Distance | If > 0, points within this distance from SelectionMesh will also be considered "inside" |
| real | Winding Threshold | Threshold used for Fast Mesh Winding Number inside/outside test (range is \[0,1\], with 1 being "inside") |
| integer | Min Num Triangle Points | number of vertices of a triangle that must be within the angular deviation for it to be selected (1,2, or 3) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Selection |  |
| object | Target Mesh |  |
