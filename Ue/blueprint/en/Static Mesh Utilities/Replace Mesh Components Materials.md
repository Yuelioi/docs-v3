---
title: Replace Mesh Components Materials
order: 30
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Static Mesh Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/StaticMeshUtilities)

Find the references of the material MaterialToReplaced on all the MeshComponents provided and replace it by NewMaterial.

Target is Static Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Mesh Components | List of MeshComponent to search from. |
| object | Material to be Replaced | Material we want to replace. |
| object | New Material | Material to replace MaterialToBeReplaced by. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
