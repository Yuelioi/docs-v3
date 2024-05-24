---
display_name: Bulk Set Convex Decomposition Collisions with Notification
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Static Mesh Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/StaticMeshUtilities)

Compute convex collisions for a set of static meshes.
Any existing collisions will be removed from the static meshes.
This method replicates what is done when invoking menu entry "Collision > Auto Convex Collision" in the Mesh Editor.

Target is Static Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Static Meshes | Set of Static mesh to add convex collision on. |
| integer | Hull Count | Maximum number of convex pieces that will be created. Must be positive. |
| integer | Max Hull Verts | Maximum number of vertices allowed for any generated convex hull. |
| integer | Hull Precision | Number of voxels to use when generating collision. Must be positive. |
| boolean | Apply Changes | Indicates if changes must be apply or not. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | A boolean indicating if the addition was successful or not. |
