---
display_name: Get Timestamp
order: 37
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Music Clock](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MusicClock)

Current bar & beat in the traditional format, where...

- bar 1 beat 1 is the beginning of the song.
- bars BEFORE bar 1 are count-in or "pickup" bars.
- beat is always 1 or greater.

Target is Music Tempometer

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Current bar & beat in the traditional format, where...- bar 1 beat 1 is the beginning of the song.- bars BEFORE bar 1 are count-in or "pickup" bars.- beat is always 1 or greater. |
