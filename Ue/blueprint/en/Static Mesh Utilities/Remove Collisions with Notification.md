---
title: Remove Collisions with Notification
order: 25
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Static Mesh Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/StaticMeshUtilities)

Remove collisions from a static mesh.
This method replicates what is done when invoking menu entries "Collision > Remove Collision" in the Mesh Editor.

Target is Static Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Static Mesh | Static mesh to remove collisions from. |
| boolean | Apply Changes | Indicates if changes must be apply or not. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | A boolean indicating if the removal was successful or not. |
