---
title: Set Mesh Per Vertex Colors
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Vertex Color](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/VertexColor)

Set all vertex colors in the TargetMesh VertexColor Overlay to the specified per-vertex colors

Target is Geometry Script Library Mesh Vertex Color Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Vertex Color List | per-vertex colors. Size must be less than or equal to the MaxVertexID of TargetMesh (ie gaps are supported) |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh |  |
