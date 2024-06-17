---
title: Open Url
order: 62
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Media Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/MediaPlayer)

Opens the specified media URL.

A return value of true indicates that the player will attempt to open
the media, but it may fail to do so later for other reasons, i.e. if
a connection to the media server timed out. Use the OnMediaOpened and
OnMediaOpenFailed delegates to detect if and when the media is ready!

Target is Media Player

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Url | The URL to open. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the URL will be opened, false otherwise. |
