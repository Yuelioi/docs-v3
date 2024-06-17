---
title: Set Marked Frame
order: 88
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Sequence](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Sequence)

- Sets the frame number for the given marked frame index. Does not maintain sort. Call SortMarkedFrames
  \*
- @InMarkIndex The given user marked frame index to edit
- @InFrameNumber The frame number to set

Target is Movie Scene Sequence Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Sequence |  |
| integer | In Mark Index |  |
| struct | In Frame Number |  |
| enum | Time Unit |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
