---
display_name: File Export Flattened Stage
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD) > [Menu Actions](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD/MenuActions)

Exports the currently opened USD Stage to a single "flattened" USD layer.
Corresponds to the "File -> Export -> All Layers" action on the USD Stage Editor menu bar.

Target is Usd Stage Editor Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Output Layer | File path (e.g. "C:/ExportFolder/out.usda") to export the flattened layer to. If this path is the empty string a dialog will be shown to let the user pick the file. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
