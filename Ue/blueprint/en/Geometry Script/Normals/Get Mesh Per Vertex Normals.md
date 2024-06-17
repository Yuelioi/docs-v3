---
title: Get Mesh Per Vertex Normals
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Normals](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Normals)

Get a list of single normal vectors for each mesh vertex in the TargetMesh, derived from the Normals Overlay.
The Normals Overlay may store multiple normals for a single vertex (ie split normals)
In such cases the normals can either be averaged, or the last normal seen will be used, depending on the bAverageSplitVertexValues parameter.

Target is Geometry Script Library Mesh Normals Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| boolean | Average Split Vertex Values | control how multiple normals at the same vertex should be interpreted |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Normal List | output normal list will be stored here. Size will be equal to the MaxVertexID of TargetMesh (not the VertexCount!) |
| boolean | Is Valid Normal Set | will be set to true if the Normal Overlay was valid |
| boolean | Has Vertex IDGaps | will be set to true if some vertex indices in TargetMesh were invalid, ie MaxVertexID > VertexCount |
| object | Target Mesh |  |
