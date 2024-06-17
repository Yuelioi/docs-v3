---
title: Apply Root Motion Move to Actor Force
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Apply force to character's movement to move to a target actor

Target is Ability Task Apply Root Motion Move to Actor Force

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| name | Task Instance Name |  |
| object | Target Actor |  |
| vector | Target Location Offset |  |
| enum | Offset Alignment |  |
| real | Duration |  |
| object | Target Lerp Speed Horizontal |  |
| object | Target Lerp Speed Vertical |  |
| boolean | Set New Movement Mode |  |
| enum | Movement Mode |  |
| boolean | Restrict Speed to Expected |  |
| object | Path Offset Curve |  |
| object | Time Mapping Curve |  |
| enum | Velocity on Finish Mode |  |
| vector | Set Velocity on Finish |  |
| real | Clamp Velocity on Finish |  |
| boolean | Disable Destination Reached Interrupt |  |
| real | Reached Destination Distance |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On Finished |  |
| boolean | Destination Reached |  |
| boolean | Timed Out |  |
| vector | Final Target Location |  |
