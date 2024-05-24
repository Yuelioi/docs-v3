---
display_name: Set Slot Enabled
order: 46
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Enables or disables the smart object slot represented by the provided handle.

Target is Smart Object Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Slot Handle | Handle to the smart object slot. |
| boolean | Enabled | If true enables the slot, if false, disables the slot. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Previous enabled state. |
