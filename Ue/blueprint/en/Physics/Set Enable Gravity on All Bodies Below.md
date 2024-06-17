---
title: Set Enable Gravity on All Bodies Below
order: 33
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Enables or disables gravity to all bodies below the given bone.
NAME_None indicates all bodies will be edited.
In that case, consider using UPrimitiveComponent::EnableGravity.

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Enable Gravity | Whether gravity should be enabled or disabled. |
| name | Bone Name | The name of the top most bone. |
| boolean | Include Self | Whether the bone specified should be edited. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
