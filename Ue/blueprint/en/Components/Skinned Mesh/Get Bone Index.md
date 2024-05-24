---
display_name: Get Bone Index
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Skinned Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/SkinnedMesh)

Find the index of bone by name. Looks in the current SkeletalMesh being used by this SkeletalMeshComponent.

Target is Skinned Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | Bone Name | Name of bone to look up |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Return Value | Index of the named bone in the current SkeletalMesh. Will return INDEX_NONE if bone not found. |
