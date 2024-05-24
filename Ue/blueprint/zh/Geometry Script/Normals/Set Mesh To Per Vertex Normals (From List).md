---
display_name: Set Mesh To Per Vertex Normals (From List)
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Normals](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Normals)

Set all normals in the TargetMesh Normals Overlay to the specified per-vertex normals

Target is Geometry Script Library Mesh Normals Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Vertex Normal List | per-vertex normals. Size must be equal to the MaxVertexID of TargetMesh (ie non-compact TargetMesh is supported) |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh |  |
