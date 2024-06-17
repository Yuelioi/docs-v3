---
title: Set Selected Layer Identifiers
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD) > [Selection](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD/Selection)

Sets the USD Stage Editor layer selection to all occurences of the layers with identifiers
in NewSelection. Provide an empty array to clear the selection.

Target is Usd Stage Editor Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | New Selection | The list of identifiers to select (e.g. \["c:/MyFolder/root.usda", "c:/MyFolder/sublayer.usda"\]) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
