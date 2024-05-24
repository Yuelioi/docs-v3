---
display_name: Get Current Section Index
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Music Clock](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MusicClock)

Returns the index of the current section for the provided time base. \[0, Num-1\] // Note: Not const as it might cause the clock to update from its source.

Target is Music Clock

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| enum | Timebase |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Return Value | Returns the index of the current section for the provided time base. \[0, Num-1\] // Note: Not const as it might cause the clock to update from its source. |
