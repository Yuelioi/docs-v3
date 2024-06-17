---
title: Calculate Velocity From Sockets
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Utilities)

This function calculates the velocity of an offset position on a bone / socket over time.
The bone's / socket's motion can be expressed within a reference frame (another bone / socket).
You need to hook up a valid PositionHistory variable to this for storage.

Target is Kismet Animation Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| real | Delta Seconds | The time passed in seconds |
| object | Component | The skeletal component to look for the bones / sockets |
| name | Socket or Bone Name | The name of the bone / socket to track. |
| name | Reference Socket or Bone | The name of the bone / socket to use as a frame of reference (or None if no frame of reference == world space). |
| enum | Socket Space | The space to use for the two sockets / bones |
| vector | Offset in Bone Space | The relative position in the space of the bone / socket to track over time. |
| struct | History | The history to use for storage. |
| integer | Number Of Samples | The number of samples to use for the history. The higher the number of samples - the smoother the velocity changes. |
| real | Velocity Min | The minimum velocity to use for normalization (if both min and max are set to 0, normalization is turned off) |
| real | Velocity Max | The maximum velocity to use for normalization (if both min and max are set to 0, normalization is turned off) |
| enum | Easing Type | The easing function to use |
| struct | Custom Curve | The curve to use if the easing type is "Custom" |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Return Value |  |
