---
display_name: Get Angular Velocity
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Motion Controller Update](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MotionControllerUpdate)

If the motion tracking system provides angular velocity at this time OutAngularVelocity will be that velocity in deg/s in unreal world space and the function will return true. Note that it is not difficult to rotate a controller at more than 0.5 or 1 rotation per second briefly and some mathmatical operations(such as conversion to quaternion) lose rotations beyond 180 degrees or 360 degrees.. In some cases that is OK becuase the resulting final rotation is the same, but in some cases it would generate incorrect results. If angular velocity is unavailable it will return false.

Target is Motion Controller Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| rotator | Out Angular Velocity |  |
| boolean | Return Value | If the motion tracking system provides angular velocity at this time OutAngularVelocity will be that velocity in deg/s in unreal world space and the function will return true. Note that it is not difficult to rotate a controller at more than 0.5 or 1 rotation per second briefly and some mathmatical operations(such as conversion to quaternion) lose rotations beyond 180 degrees or 360 degrees.. In some cases that is OK becuase the resulting final rotation is the same, but in some cases it would generate incorrect results. If angular velocity is unavailable it will return false. |
