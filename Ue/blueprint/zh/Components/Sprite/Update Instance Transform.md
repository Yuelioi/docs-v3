---
title: Update Instance Transform
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Sprite](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/Sprite)

Update the transform for the instance specified. Instance is given in local space of this component unless bWorldSpace is set. Returns True on success.

Target is Paper Grouped Sprite Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Instance Index |  |
| transform | New Instance Transform |  |
| boolean | World Space |  |
| boolean | Mark Render State Dirty |  |
| boolean | Teleport |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Update the transform for the instance specified. Instance is given in local space of this component unless bWorldSpace is set. Returns True on success. |
