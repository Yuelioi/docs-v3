---
title: Set Enable Body Gravity
order: 32
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Enables or disables gravity for the given bone.
NAME_None indicates the root body will be edited.
If the bone name given is otherwise invalid, nothing happens.

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Enable Gravity | Whether gravity should be enabled or disabled. |
| name | Bone Name | The name of the bone to modify. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
