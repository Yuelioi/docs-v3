---
title: Find Tracks by Exact Type
order: 20
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Sequence](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Sequence)

Find all tracks within a given binding of the specified type, not allowing sub-classed types

Target is Movie Scene Binding Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | In Binding | The binding to find tracks in |
| class | Track Type | A UMovieSceneTrack class type specifying the exact types of track to return |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | An array containing any tracks that are exactly the same as the type specified |
