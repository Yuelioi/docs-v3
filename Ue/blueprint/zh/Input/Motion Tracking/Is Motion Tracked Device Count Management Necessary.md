---
title: Is Motion Tracked Device Count Management Necessary
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input) > [Motion Tracking](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input/MotionTracking)

Returns true if it is necessary for the game to manage how many motion tracked devices it is asking to be tracked simultaneously.
On some platforms this is unnecessary because all supported devices can be tracked simultaneously.

Target is Motion Tracked Device Function Library

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | (Boolean) true if the game might need to manage which motion tracked devices are actively tracked. |
