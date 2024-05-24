---
display_name: Apply Mesh Shell
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Modeling](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Modeling)

Create a thickened shell from TargetMesh by offsetting the vertex positions along averaged vertex normals, inwards or outwards.
Similar to ApplyMeshOffset but also includes the initial mesh (possibly flipped, if the offset is positive)

Target is Geometry Script Library Mesh Modeling Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Options |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Create a thickened shell from TargetMesh by offsetting the vertex positions along averaged vertex normals, inwards or outwards.Similar to ApplyMeshOffset but also includes the initial mesh (possibly flipped, if the offset is positive) |
