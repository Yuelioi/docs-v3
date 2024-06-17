---
title: File Open
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD) > [Menu Actions](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD/MenuActions)

Opens an USD Stage from a file on disk.
Corresponds to the "File -> Open" action on the USD Stage Editor menu bar.

Target is Usd Stage Editor Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | File Path | File path to the USD layer to open (e.g. "C:/Folder/MyFile.usda"). If this path is the empty string a dialog will be shown to let the user pick the file. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
