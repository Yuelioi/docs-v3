---
display_name: Bone Is Child Of
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Skinned Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/SkinnedMesh)

Tests if BoneName is child of (or equal to) ParentBoneName.

Target is Skinned Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | Bone Name | Name of the bone |
| name | Parent Bone Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | true if child (strictly, not same). false otherwise Note - will return false if ChildBoneIndex is the same as ParentBoneIndex ie. must be strictly a child. |
