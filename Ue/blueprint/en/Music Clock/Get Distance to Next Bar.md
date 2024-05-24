---
display_name: Get Distance to Next Bar
order: 25
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Music Clock](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MusicClock)

Gets a value expressed in bars between 0-1 that indicates how close we are to the next bar. // Note: Not const as it might cause the clock to update from its source.

Target is Music Clock

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| enum | Timebase |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | Gets a value expressed in bars between 0-1 that indicates how close we are to the next bar. // Note: Not const as it might cause the clock to update from its source. |
