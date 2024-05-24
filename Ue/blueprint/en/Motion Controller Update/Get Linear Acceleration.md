---
display_name: Get Linear Acceleration
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Motion Controller Update](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MotionControllerUpdate)

If the motion tracking system provides linear acceleration at this time the vector will be that acceleration in cm/(s^2) in unreal world space and the function will return true. If acceleration is unavailable it will return false.

Target is Motion Controller Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Out Linear Acceleration |  |
| boolean | Return Value | If the motion tracking system provides linear acceleration at this time the vector will be that acceleration in cm/(s^2) in unreal world space and the function will return true. If acceleration is unavailable it will return false. |
