---
display_name: Update Value Of Continuous Input Injection for Player Mapping
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input)

Update the value of a continuous input injection for the given player mapping name, preserving the state of triggers and modifiers.

Target is Enhanced Input Subsystem Interface

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| name | Mapping Name | The name of the player mapping that can be used for look up an associated UInputAction object. |
| struct | Raw Value | The value to set the action to (the type will be controlled by the Action) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
