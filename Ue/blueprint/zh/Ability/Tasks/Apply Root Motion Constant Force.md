---
title: Apply Root Motion Constant Force
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Apply force to character's movement

Target is Ability Task Apply Root Motion Constant Force

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| name | Task Instance Name |  |
| vector | World Direction |  |
| real | Strength |  |
| real | Duration |  |
| boolean | Is Additive |  |
| object | Strength Over Time |  |
| enum | Velocity on Finish Mode |  |
| vector | Set Velocity on Finish |  |
| real | Clamp Velocity on Finish |  |
| boolean | Enable Gravity |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On Finish |  |
