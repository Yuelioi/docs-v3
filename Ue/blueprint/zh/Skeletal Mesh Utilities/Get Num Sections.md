---
display_name: Get Num Sections
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Skeletal Mesh Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SkeletalMeshUtilities)

Get number of sections for a LOD of a Skeletal Mesh

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
| integer | Return Value | Number of sections. Returns INDEX_NONE if invalid mesh or LOD index. |
