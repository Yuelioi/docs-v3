---
display_name: Determine Mesh Occlusion
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Scene](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Scene)

Determine which meshes are entirely hidden by other meshes in the set, when viewed from outside.

Target is Geometry Script Library Scene Utility Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Source Meshes | Meshes to test for occlusion. Note: The same mesh may appear multiple times in this array, if it is instanced with different transforms. |
| transform | Source Mesh Transforms | A transform for each source mesh. Array must have the same length as SourceMeshes. |
| object | Transparent Meshes | Transparent source meshes, to test for occlusion but which do not occlude. |
| transform | Transparent Mesh Transforms | Array of transforms for each transparent mesh |
| object | Occlude Meshes | Array of optional meshes which can occlude SourceMeshes, but for which we will not test occlusion. |
| transform | Occlude Mesh Transforms | Array of transforms for each occlude mesh. Array must have the same length as OccludeMeshes. |
| struct | Occlusion Options |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Out Mesh Is Hidden | Array will be filled with a bool per source mesh, indicating whether that mesh is hidden (true) or visible (false) |
| boolean | Out Transparent Mesh Is Hidden | Array will be filled with a bool per transparent mesh, indicating whether that mesh is hidden (true) or visible (false) |
