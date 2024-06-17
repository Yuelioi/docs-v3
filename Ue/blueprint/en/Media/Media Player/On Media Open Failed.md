---
title: On Media Open Failed
order: 49
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Media Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/MediaPlayer)

A delegate that is invoked when a media source has failed to open.

This delegate is only executed if OpenSource / OpenUrl returned true and
the media failed to open asynchronously later. It is not executed if
OpenSource / OpenUrl returned false, indicating an immediate failure.

@see OnMediaOpened
