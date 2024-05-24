---
display_name: Add Actor to Data Layers
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Data Layers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DataLayers)

Adds the provided actor to the DataLayers.

Target is Data Layer Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Actor | The actor to add to the provided DataLayers |
| object | Data Layers | A valid list of DataLayers. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the actor was added to at least one of the provided DataLayers. |
