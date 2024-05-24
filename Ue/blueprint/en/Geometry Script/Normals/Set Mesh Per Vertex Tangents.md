---
display_name: Set Mesh Per Vertex Tangents
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Normals](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Normals)

Set all tangents in the TargetMesh Tangents Overlays to the specified per-vertex tangents

Target is Geometry Script Library Mesh Normals Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Tangent XList | per-vertex tangent vectors. Size must be equal to the MaxVertexID of TargetMesh (ie non-compact TargetMesh is supported) |
| struct | Tangent YList | per-vertex bitangent/binormal vectors. Size must be equal to TangentXList |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh |  |
