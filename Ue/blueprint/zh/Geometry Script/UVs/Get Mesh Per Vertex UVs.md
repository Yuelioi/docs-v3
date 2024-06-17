---
title: Get Mesh Per Vertex UVs
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [UVs](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/UVs)

Get a list of single vertex UVs for each mesh vertex in the TargetMesh, derived from the specified UV Channel.
The UV Channel may store multiple UVs for a single vertex (along UV seams)
In such cases an arbitrary UV will be stored for that vertex, and bHasSplitUVs will be returned as true

Target is Geometry Script Library Mesh UVFunctions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | UV Channel | index of UV Channel to read |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | UVList | output UV list will be stored here. Size will be equal to the MaxVertexID of TargetMesh (not the VertexCount!) |
| boolean | Is Valid UVSet | will be set to true if the UV Channel was valid |
| boolean | Has Vertex IDGaps | will be set to true if some vertex indices in TargetMesh were invalid, ie MaxVertexID > VertexCount |
| boolean | Has Split UVs | will be set to true if there were split UVs in the UV Channel |
| object | Target Mesh |  |
