---
title: File Save
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD) > [Menu Actions](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD/MenuActions)

Saves the currently opened USD Stage back to disk, or to a new file in case it hasn't been saved yet.
Corresponds to the "File -> Save" action on the USD Stage Editor menu bar.

Target is Usd Stage Editor Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Output File Path if Unsaved | File path (e.g. "C:/Folder/MyFile.usda") to use when the currently opened stage hasn't been saved yet. If this path is the empty string a dialog will be shown to let the user pick the file. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
