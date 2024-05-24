---
display_name: Two Bone IK Function
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Utilities)

Computes the transform for two bones using inverse kinematics.

Target is Kismet Animation Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Root Pos | The input root position of the two bone chain |
| vector | Joint Pos | The input center (elbow) position of the two bone chain |
| vector | End Pos | The input end (wrist) position of the two bone chain |
| vector | Joint Target | The IK target for the write to reach |
| vector | Effector | The position of the target effector for the IK Chain. |
| boolean | Allow Stretching | If set to true the bones are allowed to stretch |
| real | Start Stretch Ratio | The ratio at which the bones should start to stretch. The higher the value, the later the stretching wil start. |
| real | Max Stretch Scale | The maximum multiplier for the stretch to reach. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Out Joint Pos | The resulting position for the center (elbow) |
| vector | Out End Pos | The resulting position for the end (wrist) |
