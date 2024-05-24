---
display_name: Enable Motion Tracking for Component
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input) > [Motion Tracking](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input/MotionTracking)

Enable tracking of the specified controller, by player index and tracked device type.

Target is Motion Tracked Device Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Motion Controller Component | (in) The motion controller component who's associated device is targeted. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | (Boolean) true if the specified device is now set to be tracked. This could fail due to tracking limits, or on invalid input. |
