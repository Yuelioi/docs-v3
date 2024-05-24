---
display_name: Add Simple Collisions with Notification
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Static Mesh Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/StaticMeshUtilities)

Add simple collisions to a static mesh.
This method replicates what is done when invoking menu entries "Collision > Add \[...\] Simplified Collision" in the Mesh Editor.

Target is Static Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Static Mesh | Mesh to generate simple collision for. |
| enum | Shape Type | Options on which simple collision to add to the mesh. |
| boolean | Apply Changes | Indicates if changes must be apply or not. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value | An integer indicating the index of the collision newly created. A negative value indicates the addition failed. |
