---
title: Set Bone Transform
order: 26
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Control Rig](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ControlRig_1)

Sets the transform of the bone in the requested space

Target is Control Rig Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Bone Name | The name of the bone to set the transform for |
| transform | Transform |  |
| enum | Space | The space to set the transform in |
| real | Weight | The weight of how much the change should be applied (0.0 to 1.0) |
| boolean | Propagate to Children | If true the child bones will be moved together with the affected bone |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
