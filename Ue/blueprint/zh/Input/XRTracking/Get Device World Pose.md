---
title: Get Device World Pose
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input) > [XRTracking](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input/XRTracking)

Cross XR-System query that returns a specific device's position and orientation in world space.

Target is Head Mounted Display Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | XRDevice Id | Specifies the device you're querying for. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Is Tracked | \[out\] Details if the specified device is tracked (i.e. should the rest of the outputs be used) |
| rotator | Orientation | \[out\] Represents the device's current rotation - NOTE: this value is not late updated and will be behind the render thread |
| boolean | Has Positional Tracking | \[out\] Details if the specified device has positional tracking (i.e. if the position output should be used) |
| vector | Position | \[out\] Represents the device's current position - NOTE: this value is not late updated and will be behind the render thread |
