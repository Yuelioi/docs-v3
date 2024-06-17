---
title: Get Pose
order: 67
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Returns the current / initial pose of the hierarchy

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| boolean | Initial | If set to true the initial pose will be returned |
| boolean | Include Transient Controls | If true the transient controls will be included in the pose |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The pose of the hierarchy |
