---
title: Get Twist and Swing Angle Of Delta Rotation from Ref Pose
order: 20
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Skinned Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/SkinnedMesh)

Get Twist and Swing Angle in Degree of Delta Rotation from Reference Pose in Local space

First this function gets rotation of current, and rotation of ref pose in local space, and
And gets twist/swing angle value from refpose aligned.

Target is Skinned Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | Bone Name | Name of the bone |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Out Twist Angle | TwistAngle in degree |
| real | Out Swing Angle | SwingAngle in degree |
| boolean | Return Value | true if succeed. False otherwise. Often due to incorrect bone name. |
