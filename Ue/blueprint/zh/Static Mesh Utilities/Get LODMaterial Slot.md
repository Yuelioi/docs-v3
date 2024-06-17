---
title: Get LODMaterial Slot
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Static Mesh Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/StaticMeshUtilities)

Gets the material slot used for a specific LOD section.

Target is Static Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Static Mesh | Static mesh to get the material index from. |
| integer | LODIndex | Index of the StaticMesh LOD. |
| integer | Section Index | Index of the StaticMesh Section. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value | MaterialSlotIndex Index of the material slot used by the section or INDEX_NONE in case of error. |
