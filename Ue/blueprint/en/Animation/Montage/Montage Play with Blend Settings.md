---
title: Montage Play with Blend Settings
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Montage](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Montage)

Plays an animation montage. Same as Montage_Play, but you can overwrite all of the montage's default blend in settings.

Target is Anim Instance

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Montage to Play |  |
| struct | Blend in Settings |  |
| real | In Play Rate |  |
| enum | Return Value Type |  |
| real | In Time to Start Montage At |  |
| boolean | Stop All Montages |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Return Value | Plays an animation montage. Same as Montage_Play, but you can overwrite all of the montage's default blend in settings. |
