---
title: Duplicate Asset with Dialog and Title
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Asset Tools](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/AssetTools)

Opens an asset picker dialog and creates an asset with the specified name and path.
Uses OriginalObject as the duplication source.
Uses DialogTitle as the dialog's title.

Target is Asset Tools

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| string | Asset Name |  |
| string | Package Path |  |
| object | Original Object |  |
| text | Dialog Title |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Opens an asset picker dialog and creates an asset with the specified name and path.Uses OriginalObject as the duplication source.Uses DialogTitle as the dialog's title. |
