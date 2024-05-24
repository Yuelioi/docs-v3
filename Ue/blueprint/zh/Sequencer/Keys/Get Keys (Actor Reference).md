---
display_name: Get Keys (Actor Reference)
order: 28
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Keys](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Keys)

Gets all of the keys in this channel.

Target is Movie Scene Scripting Actor Reference Channel

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | An array of UMovieSceneScriptingActorReferenceKeys contained by this channel. Returns all keys even if clipped by the owning section's boundaries or outside of the current sequence play range. |
