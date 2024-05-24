---
display_name: Set SmartObject Enabled (specific reason)
order: 49
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Enables or disables the smart object for the specified reason.

Target is Smart Object Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Reason Tag | Valid Tag to specify the reason for changing the enabled state of the object. Method will ensure if not valid (i.e. None). |
| boolean | Enabled | If true enables the smart object, disables otherwise. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Status Changed | false if it was not possible to change the enabled state (ie. if it's not registered or there is no smart object subsystem). |
