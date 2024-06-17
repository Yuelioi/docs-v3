---
title: Paste Tracks
order: 46
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Level Sequence Editor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LevelSequenceEditor)

Paste tracks
Paste tracks from the given TextToImport string (used in conjunction with CopyTracks).
If TextToImport is empty, the contents of the clipboard will be used.

Target is Level Sequence Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Text to Import |  |
| struct | Paste Tracks Params |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out Tracks |  |
| boolean | Return Value | Paste tracksPaste tracks from the given TextToImport string (used in conjunction with CopyTracks).If TextToImport is empty, the contents of the clipboard will be used. |
