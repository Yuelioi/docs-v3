---
display_name: Get Time (Event)
order: 60
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Keys](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Keys)

Gets the time for this key from the owning channel.

Target is Movie Scene Scripting Event Key

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| enum | Time Unit | Should the time be returned in Display Rate frames (possibly with a sub-frame value) or in Tick Resolution with no sub-frame values? |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The time of this key which combines both the frame number and the sub-frame it is on. Sub-frame will be zero if you request Tick Resolution. |
