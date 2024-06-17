---
title: Copy Bindings
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Level Sequence Editor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LevelSequenceEditor)

Copy bindings
The copied bindings will be saved to the clipboard as well as assigned to the ExportedText string.
The ExportedTest string can be used in conjunction with PasteBindings if, for example, pasting copy/pasting multiple
bindings without relying on a single clipboard.

Target is Level Sequence Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Bindings |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Exported Text |  |
