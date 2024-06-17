---
title: Calculate Velocity From Position History
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Utilities)

This function calculates the velocity of a position changing over time.
You need to hook up a valid PositionHistory variable to this for storage.

Target is Kismet Animation Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| real | Delta Seconds | The time passed in seconds |
| vector | Position | The position to track over time. |
| struct | History | The history to use for storage. |
| integer | Number Of Samples | The number of samples to use for the history. The higher the number of samples - the smoother the velocity changes. |
| real | Velocity Min | The minimum velocity to use for normalization (if both min and max are set to 0, normalization is turned off) |
| real | Velocity Max | The maximum velocity to use for normalization (if both min and max are set to 0, normalization is turned off) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Return Value |  |
