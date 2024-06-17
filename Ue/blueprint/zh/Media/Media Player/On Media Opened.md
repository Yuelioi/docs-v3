---
title: On Media Opened
order: 50
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Media Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/MediaPlayer)

A delegate that is invoked when a media source has been opened.

Depending on whether the underlying player implementation opens the media
synchronously or asynchronously, this event may be executed before or
after the call to OpenSource / OpenUrl returns.

@see OnMediaOpenFailed, OnTracksChanged
