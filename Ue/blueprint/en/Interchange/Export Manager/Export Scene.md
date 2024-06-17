---
title: Export Scene
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Interchange](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Interchange) > [Export Manager](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Interchange/ExportManager)

Call this to start a scene export process. The caller must specify a source data.

Target is Interchange Manager

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | World | The scene to export. |
| boolean | Is Automated | If true, the import process will not show any UI or dialogs. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the export succeeds, or false otherwise. |
