---
title: Remove Bone Animation
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation Blueprint Library](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AnimationBlueprintLibrary) > [Bones](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AnimationBlueprintLibrary/Bones)

Removes an Animation Curve by Name from the given Animation Sequence (Raw Animation Curves \[Names\] may not be removed from the Skeleton)

Target is Animation Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Animation Sequence | : AnimSequence |
| name | Bone Name | : Name of bone track user wants to remove |
| boolean | Include Children | : true if user wants to include all children of BoneName |
| boolean | Finalize | : If you set this to true, it will trigger compression. If you set bFinalize to be false, you'll have to manually trigger Finalize. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
