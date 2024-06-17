---
title: Un Hide Bone by Name
order: 43
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Skinned Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/SkinnedMesh)

UnHide the specified bone with name. Currently this just enforces a scale of 0 for the hidden bones.
Compared to HideBone By Index - This keeps track of list of bones and update when LOD changes

Target is Skinned Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Bone Name | Name of bone to unhide |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
