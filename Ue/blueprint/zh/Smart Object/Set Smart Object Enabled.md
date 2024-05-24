---
display_name: Set Smart Object Enabled
order: 47
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Marks all smart objects for an actor as enabled or not according to 'bEnabled'. A smart object marked as Enabled is available for queries.

Target is Smart Object Blueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Smart Object Actor | The actor containing the smart objects to enable/disable |
| boolean | Enabled | Whether the smart objects should be enabled or not |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Success | True if the requested operation succeeded; false otherwise |
