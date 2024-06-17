---
title: Apply Root Motion Move to Force
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Apply force to character's movement

Target is Ability Task Apply Root Motion Move to Force

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| name | Task Instance Name |  |
| vector | Target Location |  |
| real | Duration |  |
| boolean | Set New Movement Mode |  |
| enum | Movement Mode |  |
| boolean | Restrict Speed to Expected |  |
| object | Path Offset Curve |  |
| enum | Velocity on Finish Mode |  |
| vector | Set Velocity on Finish |  |
| real | Clamp Velocity on Finish |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On Timed Out |  |
| exec | On Timed Out And Destination Reached |  |
