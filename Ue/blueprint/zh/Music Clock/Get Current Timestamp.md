---
display_name: Get Current Timestamp
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Music Clock](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MusicClock)

Returns the "classic" musical timestamp in the form Bar (int) & Beat (float). In this form...

- Bar 1, Beat 1.0 is the "beginning of the song" AFTER count-in/pickups
- Bar 0, Beat 1.0 would be one bar BEFORE the "beginning of the song"... eg. a bar of count-in or pickup.
- While Bar can be positive or negative, Beat is always >= 1.0 and is read as "beat in the bar". Again... '1' based!
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
| struct | Return Value | Returns the "classic" musical timestamp in the form Bar (int) & Beat (float). In this form...- Bar 1, Beat 1.0 is the "beginning of the song" AFTER count-in/pickups- Bar 0, Beat 1.0 would be one bar BEFORE the "beginning of the song"... eg. a bar of count-in or pickup.- While Bar can be positive or negative, Beat is always >= 1.0 and is read as "beat in the bar". Again... '1' based!Note: Not const as it might cause the clock to update from its source. |
