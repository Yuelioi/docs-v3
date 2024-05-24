---
display_name: Get Num Verts
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Skeletal Mesh Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SkeletalMeshUtilities)

Get number of mesh vertices for an LOD of a Skeletal Mesh

Target is Skeletal Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| object | Skeletal Mesh | Mesh to get number of vertices from. |
| integer | LODIndex | Index of the mesh LOD. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Return Value | Number of vertices. Returns 0 if invalid mesh or LOD index. |
