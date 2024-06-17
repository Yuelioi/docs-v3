---
title: Set Skinned Asset and Update
order: 36
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Skinned Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/SkinnedMesh)

Change the SkinnedAsset that is rendered for this Component. Will re-initialize the animation tree etc.

Target is Skinned Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | New Mesh | New mesh to set for this component |
| boolean | Reinit Pose | Whether we should keep current pose or reinitialize. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
