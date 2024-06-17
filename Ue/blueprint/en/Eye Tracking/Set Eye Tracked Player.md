---
title: Set Eye Tracked Player
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Eye Tracking](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EyeTracking)

Specifies player being eye-tracked. This is not necessary for all devices, but is necessary for some to determine viewport properties, etc.

Target is Eye Tracker Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Player Controller | The player for whom we are tracking. Null can be ok for some devices, but this may be necessary for others to determine viewport properties, etc. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
