---
title: Find Tracks by Type
order: 21
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Sequence](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Sequence)

Find all tracks within a given binding of the specified type

Target is Movie Scene Binding Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | In Binding | The binding to find tracks in |
| class | Track Type | A UMovieSceneTrack class type specifying which types of track to return |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | An array containing any tracks that match the type specified |
