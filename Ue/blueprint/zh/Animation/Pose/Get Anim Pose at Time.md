---
title: Get Anim Pose at Time
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Pose](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Pose)

Evaluates an Animation Sequence Base to generate a valid Anim Pose instance

Target is Anim Pose Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Animation Sequence Base | Animation sequence base to evaluate the pose from |
| real | Time | Time at which the pose should be evaluated |
| struct | Evaluation Options | Options determining the way the pose should be evaluated |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Pose | Anim Pose to hold the evaluated data |
