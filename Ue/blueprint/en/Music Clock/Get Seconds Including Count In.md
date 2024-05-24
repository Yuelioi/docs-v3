---
display_name: Get Seconds Including Count In
order: 28
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Music Clock](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MusicClock)

Time from the beginning of the authored music content.
NOTE: INCLUDES time for count-in and pickup bars.
Note: Not const as it might cause the clock to update from its source.

Target is Music Clock

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| enum | Timebase |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | Time from the beginning of the authored music content.NOTE: INCLUDES time for count-in and pickup bars.Note: Not const as it might cause the clock to update from its source. |
