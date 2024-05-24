---
display_name: Select Actors in Data Layers
order: 40
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Data Layers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DataLayers)

Selects/de-selects actors belonging to the DataLayers.

Target is Data Layer Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Data Layers | A valid list of DataLayers. |
| boolean | Select | If true actors are selected; if false, actors are deselected. |
| boolean | Notify | If true the Editor is notified of the selection change; if false, the Editor will not be notified |
| boolean | Select Even if Hidden | \[optional\] If true even hidden actors will be selected; if false, hidden actors won't be selected. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if at least one actor was selected/deselected. |
