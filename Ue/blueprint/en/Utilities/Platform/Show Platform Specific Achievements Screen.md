---
title: Show Platform Specific Achievements Screen
order: 27
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Platform](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Platform)

Displays the built-in achievements GUI (iOS and Android only; this function may be renamed or moved in a future release)

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Specific Player | Specific player's achievements to show. May not be supported on all platforms. If null, defaults to the player with ControllerId 0 |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
