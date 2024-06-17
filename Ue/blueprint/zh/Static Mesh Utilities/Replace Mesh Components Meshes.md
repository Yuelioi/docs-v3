---
title: Replace Mesh Components Meshes
order: 32
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Static Mesh Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/StaticMeshUtilities)

Find the references of the mesh MeshToBeReplaced on all the MeshComponents provided and replace it by NewMesh.
The editor should not be in play in editor mode.

Target is Static Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Mesh Components | List of MeshComponent to search from. |
| object | Mesh to be Replaced | Mesh we want to replace. |
| object | New Mesh | Mesh to replace MeshToBeReplaced by. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
