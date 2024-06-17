---
title: Enable Motion Tracking Of Source
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input) > [Motion Tracking](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input/MotionTracking)

Enable tracking of the specified controller, by player index and tracked device type.

Target is Motion Tracked Device Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| integer | Player Index | (in) The index of the player. |
| name | Source Name | (in) The device id. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | (Boolean) true if the specified device is now set to be tracked. This could fail due to tracking limits, or on invalid input. |
