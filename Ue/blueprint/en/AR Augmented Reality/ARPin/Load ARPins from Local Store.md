---
display_name: Load ARPins from Local Store
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AR Augmented Reality](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality) > [ARPin](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality/ARPin)

Load all ARPins from local save
Note: Multiple loads of a saved pin may result in duplicate pins OR overwritten pins. It is reccomended to only load once.

Target is ARBlueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| name | Return Value | Map of SaveName:ARPin. |
