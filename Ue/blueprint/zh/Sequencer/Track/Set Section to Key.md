---
display_name: Set Section to Key
order: 24
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Track](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Track)

Set the section to key for this track. When properties for this section are modified externally,
this section will receive those modifications and act accordingly (add/update keys). This is
especially useful when there are multiple overlapping sections.

Target is Movie Scene Track Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Track | The track to set the section to key for |
| object | Section | The section to key for this track |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
