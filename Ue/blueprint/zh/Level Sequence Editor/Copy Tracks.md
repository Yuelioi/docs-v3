---
title: Copy Tracks
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Level Sequence Editor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LevelSequenceEditor)

Copy tracks
The copied tracks will be saved to the clipboard as well as assigned to the ExportedText string.
The ExportedTest string can be used in conjunction with PasteTracks if, for example, pasting copy/pasting multiple
tracks without relying on a single clipboard.

Target is Level Sequence Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Tracks |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Exported Text |  |
