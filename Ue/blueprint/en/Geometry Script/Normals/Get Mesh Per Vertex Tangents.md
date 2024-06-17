---
title: Get Mesh Per Vertex Tangents
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Normals](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Normals)

Get a list of single tangent vectors for each mesh vertex in the TargetMesh, derived from the Tangents Overlays.
The Tangents Overlay may store multiple tangents for a single vertex (ie split tangents)
In such cases the tangents can either be averaged, or the last tangent seen will be used, depending on the bAverageSplitVertexValues parameter.

Target is Geometry Script Library Mesh Normals Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| boolean | Average Split Vertex Values | control how multiple tangents at the same vertex should be interpreted |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Tangent XList | output Tangent "X" vectors list will be stored here. Size will be equal to the MaxVertexID of TargetMesh (not the VertexCount!) |
| struct | Tangent YList | output Tangent "Y" vectors (Binormal/Bitangent) list will be stored here. Size will be equal to TangentXList |
| boolean | Is Valid Tangent Set | will be set to true if the Tangent Overlay was valid |
| boolean | Has Vertex IDGaps | will be set to true if some vertex indices in TargetMesh were invalid, ie MaxVertexID > VertexCount |
| object | Target Mesh |  |
