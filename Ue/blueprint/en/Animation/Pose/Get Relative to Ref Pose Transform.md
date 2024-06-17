---
title: Get Relative to Ref Pose Transform
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Pose](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Pose)

Retrieves the relative transform between reference and animated bone transform

Target is Anim Pose Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Pose | Anim Pose to retrieve the transform from |
| name | Bone Name | Name of the bone to retrieve the relative transform for |
| enum | Space | Space in which the transform should be retrieved |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Return Value | Relative transform in requested space for bone if found, otherwise return identity transform |
