---
title: Export Selected Layers
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD) > [Menu Actions](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD/MenuActions)

Exports the currently selected layers on the USD Stage Editor to brand new files in a new location.
Corresponds to right-clicking selected layers on the USD Stage Editor and picking "Export".

Target is Usd Stage Editor Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Output Directory | Directory path (e.g. "C:/ExportFolder/") to receive the exported files. If this path is the empty string a dialog will be shown to let the user pick the directory. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
