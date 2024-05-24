---
display_name: Add Track
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Sequence](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Sequence)

Add a new track to the specified binding

Target is Movie Scene Binding Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | In Binding | The binding to add tracks to |
| class | Track Type | A UMovieSceneTrack class type specifying the type of track to create |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The newly created track, if successful |
