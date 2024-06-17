---
title: Start Legacy Camera Shake
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Camera Shakes](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/CameraShakes)

Backwards compatible method used by core BP redirectors. This is needed because the return value is specifically a legacy camera shake,
which some BP logic often uses directly to set oscillator/anim properties.

Target is Legacy Camera Shake

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Player Camera Manager |  |
| class | Shake Class |  |
| real | Scale |  |
| enum | Play Space |  |
| rotator | User Play Space Rot |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Backwards compatible method used by core BP redirectors. This is needed because the return value is specifically a legacy camera shake,which some BP logic often uses directly to set oscillator/anim properties. |
