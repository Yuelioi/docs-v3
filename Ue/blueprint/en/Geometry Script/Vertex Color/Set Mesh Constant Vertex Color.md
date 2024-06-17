---
title: Set Mesh Constant Vertex Color
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Vertex Color](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/VertexColor)

Set all vertex colors (optionally specific channels) in the TargetMesh VertexColor Overlay to a constant value

Target is Geometry Script Library Mesh Vertex Color Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| linearcolor | Color | the constant color to set |
| struct | Flags | specify which RGBA channels to set (default all channels) |
| boolean | Clear Existing |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh |  |
