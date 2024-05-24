---
display_name: Set Time (Bool)
order: 117
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Keys](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Keys)

Sets the time for this key in the owning channel. Will replace any key that already exists at that frame number in this channel.

Target is Movie Scene Scripting Bool Key

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | New Frame Number | What frame should this key be moved to? This should be in the time unit specified by TimeUnit. |
| real | Sub Frame | If using Display Rate time, what is the sub-frame this should go to? Clamped \[0-1), and ignored with when TimeUnit is set to Tick Resolution. |
| enum | Time Unit | Should the NewFrameNumber be interpreted as Display Rate frames or in Tick Resolution? |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
