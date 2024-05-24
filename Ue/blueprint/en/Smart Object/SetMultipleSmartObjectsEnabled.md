---
display_name: SetMultipleSmartObjectsEnabled
order: 52
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Marks all smart objects for a list of actors as enabled or not according to 'bEnabled'. A smart object marked as Enabled is available for queries.

Target is Smart Object Blueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Smart Object Actors | The actors containing the smart objects to enable/disable |
| boolean | Enabled | Whether the smart objects should be in the simulation (added) or not (removed) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Success | True if all actors were valid and the requested operation succeeded; false otherwise |
