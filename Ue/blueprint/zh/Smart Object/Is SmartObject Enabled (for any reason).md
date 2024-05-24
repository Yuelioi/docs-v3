---
display_name: Is SmartObject Enabled (for any reason)
order: 34
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Returns the enabled state of the smart object represented by the provided handle regardless of the disabled reason.

Target is Smart Object Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Handle | Handle to the smart object. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Enabled | True when associated smart object is found and set to be enabled. False otherwise. |
