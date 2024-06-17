---
title: Pose Search Generate Trajectory
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Pose Search](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/PoseSearch)

Generates a prediction trajectory based of the current character intent.

Target is Pose Search Trajectory Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Anim Instance |  |
| struct | In Trajectory Data |  |
| real | In Delta Time |  |
| struct | In Out Trajectory |  |
| real | In Out Desired Controller Yaw Last Update |  |
| real | In History Sampling Interval |  |
| integer | In Trajectory History Count |  |
| real | In Prediction Sampling Interval |  |
| integer | In Trajectory Prediction Count |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Trajectory |  |
