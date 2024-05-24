---
display_name: Set Playback Position
order: 23
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Timeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/Timeline)

Jump to a position in the timeline.

Target is Timeline Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | New Position |  |
| boolean | Fire Events | If true, event functions that are between current position and new playback position will fire. |
| boolean | Fire Update | If true, the update output exec will fire after setting the new playback position. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
