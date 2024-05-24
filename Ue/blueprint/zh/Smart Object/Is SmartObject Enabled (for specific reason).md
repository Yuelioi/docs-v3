---
display_name: Is SmartObject Enabled (for specific reason)
order: 35
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Returns the enabled state of the smart object based on a specific reason.

Target is Smart Object Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Reason Tag | Valid Tag to test if enabled for a specific reason. Method will ensure if not valid (i.e. None). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Enabled | True when associated smart object is set to be enabled. False otherwise. |
