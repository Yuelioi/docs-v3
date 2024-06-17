---
title: Set Time Delay
order: 78
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Media Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/MediaPlayer)

Delay of the player's time.

This setting can be used to manually sync multiple sources.
Set to 1 seconds, if you would like that Player to play 1 second behind its current time.
If the value is too big, it is possible that the player would not hold that frame for that long.

Target is Media Player

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Time Delay |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
