---
title: Get Delta Transform from Ref Pose
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Skinned Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/SkinnedMesh)

Get delta transform from reference pose based on BaseNode.
This uses last frame up-to-date transform, so it will have a frame delay if you use this info in the AnimGraph

Target is Skinned Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | Bone Name | Name of the bone |
| name | Base Name | Name of the base bone - if none, it will use parent as a base |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Return Value | the delta transform from refpose in that given space (BaseName) |
