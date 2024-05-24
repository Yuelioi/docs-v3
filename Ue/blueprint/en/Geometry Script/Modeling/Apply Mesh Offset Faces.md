---
display_name: Apply Mesh Offset Faces
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Modeling](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Modeling)

Apply an Offset to the faces of TargetMesh identified by the Selection, or all faces if the Selection is empty.
The Offset direction at each vertex can be derived from the averaged vertex normals or per-triangle normals.

Target is Geometry Script Library Mesh Modeling Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Options |  |
| struct | Selection |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Apply an Offset to the faces of TargetMesh identified by the Selection, or all faces if the Selection is empty.The Offset direction at each vertex can be derived from the averaged vertex normals or per-triangle normals. |
