---
title: Play To
order: 35
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Player)

Play from the current position to the requested position and pause. If requested position is before the current position,
playback will be reversed. Playback to the requested position will be cancelled if Stop() or Pause() is invoked during this
playback.

Target is Movie Scene Sequence Player

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Playback Params | The position settings (ie. the position to play to) |
| struct | Play to Params |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
