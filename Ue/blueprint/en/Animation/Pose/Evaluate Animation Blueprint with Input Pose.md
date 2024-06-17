---
title: Evaluate Animation Blueprint with Input Pose
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Pose](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Pose)

Evaluates an Animation Blueprint instance, using the provided Anim Pose and its Input Pose value, generating a valid Anim Pose using the result. Warning this function may cause performance issues.

Target is Anim Pose Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Input Pose | Anim Pose used to populate the input pose node value inside of the Animation Blueprint |
| object | Target Skeletal Mesh | USkeletalMesh object used as the target skeletal mesh, should have same USkeleton as InputPose and Animation Blueprint |
| object | Animation Blueprint | Animation Blueprint to generate an AnimInstance with, used to evaluate the output Anim Pose |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Pose | Anim pose to hold the data from evaluating the Animation Blueprint instance |
