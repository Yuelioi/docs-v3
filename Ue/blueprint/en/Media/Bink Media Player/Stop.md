---
title: Stop
order: 26
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Bink Media Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/BinkMediaPlayer)

Stops playback and unloads the video from memory. If you want to start the video again you'll need to call InitializePlayer.
MediaEvent will broadcast EMediaEvent::MediaClosed.

Target is Bink Media Player

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
