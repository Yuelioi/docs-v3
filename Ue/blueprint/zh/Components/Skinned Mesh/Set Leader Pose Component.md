---
title: Set Leader Pose Component
order: 28
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Skinned Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/SkinnedMesh)

Set LeaderPoseComponent for this component

Target is Skinned Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | New Leader Bone Component | New LeaderPoseComponent |
| boolean | Force Update | If false, the function will be skipped if NewLeaderBoneComponent is the same as currently setup (default) |
| boolean | In Follower Should Tick Pose | If false, Follower components will not execute TickPose (default) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
