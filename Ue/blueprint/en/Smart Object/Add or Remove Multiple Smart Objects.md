---
display_name: Add or Remove Multiple Smart Objects
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Adds to the simulation all smart objects for multiple actors or removes them according to 'bAdd'.

Target is Smart Object Blueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Smart Object Actors | The actors containing the smart objects to add or remove from the simulation |
| boolean | Add | Whether the smart objects should be added or removed from the simulation |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Success | True if all actors were valid and the requested operation succeeded; false otherwise |
