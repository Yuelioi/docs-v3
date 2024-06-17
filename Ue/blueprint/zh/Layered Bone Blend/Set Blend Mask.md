---
title: Set Blend Mask
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Layered Bone Blend](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LayeredBoneBlend)

Sets the currently-used blend mask for a blended input pose by name.

Target is Layered Bone Blend Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Update Context | The update context to use. This is used to extract the current skeleton to derive the blend mask from |
| struct | Layered Bone Blend | A reference to the node |
| integer | Pose Index | The pose index to set the blend mask for |
| name | Blend Mask Name | The name of the blend mask to use |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value |  |
