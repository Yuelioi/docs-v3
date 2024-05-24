---
display_name: Get All Channels
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Section](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Section)

Find all channels that belong to the specified UMovieSceneSection. Some sections have many channels (such as
Transforms containing 9 double channels to represent Translation/Rotation/Scale), and a section may have mixed
channel types.

Target is Movie Scene Section Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Section | The section to use. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | An array containing any key channels that match the type specified |
