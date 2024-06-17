---
title: Paste Folders
order: 44
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Level Sequence Editor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LevelSequenceEditor)

Paste folders
Paste folders from the given TextToImport string (used in conjunction with CopyFolders).
If TextToImport is empty, the contents of the clipboard will be used.

Target is Level Sequence Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Text to Import |  |
| struct | Paste Folders Params |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out Folders |  |
| boolean | Return Value | Paste foldersPaste folders from the given TextToImport string (used in conjunction with CopyFolders).If TextToImport is empty, the contents of the clipboard will be used. |
