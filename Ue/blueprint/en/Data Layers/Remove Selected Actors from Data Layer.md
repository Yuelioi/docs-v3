---
display_name: Remove Selected Actors from Data Layer
order: 35
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Data Layers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DataLayers)

Removes the selected actors from the DataLayer.

Target is Data Layer Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Data Layer | A DataLayer. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if at least one actor was added. false is returned if all selected actors already belong to the DataLayer. |
