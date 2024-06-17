---
title: Get Linear Velocity
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Motion Controller Update](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MotionControllerUpdate)

If the motion tracking system provides linear velocity at this time the vector will be that velocity in cm/s in unreal world space and the function will return true. If velocity is unavailable it will return false.

Target is Motion Controller Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Out Linear Velocity |  |
| boolean | Return Value | If the motion tracking system provides linear velocity at this time the vector will be that velocity in cm/s in unreal world space and the function will return true. If velocity is unavailable it will return false. |
