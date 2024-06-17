---
title: Get Keys By Index (Float)
order: 42
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Keys](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Keys)

Gets the keys in this channel specified by the specific index
@Indices The indices from which to get the keys from

Target is Movie Scene Scripting Float Channel

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| integer | Indices |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | An array of UMovieSceneScriptingKey's contained by this channel. Returns all keys specified by the indices, even if out of range. |
