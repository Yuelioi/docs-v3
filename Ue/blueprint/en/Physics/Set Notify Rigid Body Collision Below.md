---
title: Set Notify Rigid Body Collision Below
order: 47
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Changes the value of bNotifyRigidBodyCollision on all bodies below a given bone

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | New Notify Rigid Body Collision | The value to assign to bNotifyRigidBodyCollision |
| name | Bone Name | Name of the body to turn hit notifies on (and below) |
| boolean | Include Self | Whether to modify the given body (useful for roots with multiple children) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
