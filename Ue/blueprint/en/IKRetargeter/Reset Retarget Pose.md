---
display_name: Reset Retarget Pose
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [IKRetargeter](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/IKRetargeter)

Reset a retarget pose for the specified bones.
If BonesToReset is Empty, will removes all stored deltas, returning pose to reference pose

Target is IKRetargeter Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Pose to Reset |  |
| name | Bones to Reset |  |
| enum | Source or Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
