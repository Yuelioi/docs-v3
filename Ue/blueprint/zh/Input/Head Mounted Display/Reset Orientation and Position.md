---
display_name: Reset Orientation and Position
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input) > [Head Mounted Display](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input/HeadMountedDisplay)

Resets orientation by setting roll and pitch to 0, assuming that current yaw is forward direction and assuming
current position as a 'zero-point' (for positional tracking).

Target is Head Mounted Display Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| real | Yaw | (in) the desired yaw to be set after orientation reset. |
| enum | Options | (in) specifies either position, orientation or both should be reset. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
