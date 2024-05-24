---
display_name: Get Section Visible in Ray Tracing
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Skeletal Mesh Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SkeletalMeshUtilities)

Get bVisibleInRayTracing from a section of a LOD of a Skeletal Mesh

Target is Skeletal Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| object | Skeletal Mesh | Mesh to get number of vertices from. |
| integer | LODIndex | Index of the mesh LOD. |
| integer | Section Index | Index of the LOD section. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Out Visible in Ray Tracing | The function will set the bVisibleInRayTracing used by the section |
| boolean | Return Value | false if invalid mesh or LOD index or section index. |
