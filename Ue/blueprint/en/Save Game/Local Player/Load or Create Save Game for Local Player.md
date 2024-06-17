---
title: Load or Create Save Game for Local Player
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Save Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SaveGame) > [Local Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SaveGame/LocalPlayer)

Synchronously loads a save game object in the specified slot for the local player, stalling the main thread until it completes.
This will return null for invalid parameters, but will create a new instance if the parameters are valid but loading fails.

Target is Local Player Save Game

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| class | Save Game Class |  |
| object | Local Player Controller |  |
| string | Slot Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Synchronously loads a save game object in the specified slot for the local player, stalling the main thread until it completes.This will return null for invalid parameters, but will create a new instance if the parameters are valid but loading fails. |
