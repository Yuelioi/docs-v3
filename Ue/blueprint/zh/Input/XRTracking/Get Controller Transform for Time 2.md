---
display_name: Get Controller Transform for Time 2
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input) > [XRTracking](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input/XRTracking)

Get the transform and potentially velocity data at a specified time near the current frame in unreal world space.
This is intended for use with sub-frame input action timing data from SetXRTimedInputActionDelegate, or future support for timestamps in the core input system.
The valid time window is platform dependent, but the intention per OpenXR is to fetch transforms for times from, at most, the previous few frames in the past or future.
The OpenXR spec suggests that 50ms in the past should return an accurate result. There is no guarantee for the future, but the underlying system is likely to have been
designed to predict out to about 50ms as well.
On some platforms this will always just return a cached position and rotation, ignoring time. bTimeWasUsed will be false in that case.
AngularVelocity is a Rotator in degrees/second.
Be aware that this Rotator may have windings (rotations greater than 360 degrees) and some mathmatical operations (such as conversion to quaternion) will remove the windings.
In some cases that is OK becuase the resulting final rotation is the same, but in some cases it would generate incorrect results.

Target is Head Mounted Display Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | World Context |  |
| integer | Controller Index |  |
| name | Motion Source |  |
| struct | Time |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Time Was Used |  |
| rotator | Orientation |  |
| vector | Position |  |
| boolean | Provided Linear Velocity |  |
| vector | Linear Velocity |  |
| boolean | Provided Angular Velocity |  |
| rotator | Angular Velocity |  |
| boolean | Provided Linear Acceleration |  |
| vector | Linear Acceleration |  |
| boolean | Return Value | Get the transform and potentially velocity data at a specified time near the current frame in unreal world space.This is intended for use with sub-frame input action timing data from SetXRTimedInputActionDelegate, or future support for timestamps in the core input system.The valid time window is platform dependent, but the intention per OpenXR is to fetch transforms for times from, at most, the previous few frames in the past or future.The OpenXR spec suggests that 50ms in the past should return an accurate result. There is no guarantee for the future, but the underlying system is likely to have beendesigned to predict out to about 50ms as well.On some platforms this will always just return a cached position and rotation, ignoring time. bTimeWasUsed will be false in that case.AngularVelocity is a Rotator in degrees/second.Be aware that this Rotator may have windings (rotations greater than 360 degrees) and some mathmatical operations (such as conversion to quaternion) will remove the windings.In some cases that is OK becuase the resulting final rotation is the same, but in some cases it would generate incorrect results. |
