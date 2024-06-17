---
title: Set AR World Origin Location and Rotation
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AR Augmented Reality](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality) > [Alignment](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality/Alignment)

For a point P in the AR local space, whose location and rotation are "OriginLocation" and "OriginRotation" in the world space
modify the alignment transform so that the same point P will be transformed to the origin in the world space.
@bIsTransformInWorldSpace: whether "OriginLocation" and "OriginRotation" are specified in UE4's world space or AR system's local space.
@bMaintainUpDirection: if set, only the yaw roation of the alignment transform will be modified, pitch and roll will be zeroed out.

Target is ARBlueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Origin Location |  |
| rotator | Origin Rotation |  |
| boolean | Is Transform in World Space |  |
| boolean | Maintain Up Direction |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
