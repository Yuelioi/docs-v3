---
title: Async Load or Create Save Game for Local Player
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Save Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SaveGame) > [Local Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SaveGame/LocalPlayer)

Asynchronously loads a save game object in the specified slot for the local player, if this returns true the delegate will get called later.
False means the load was never scheduled, otherwise it will create and initialize a new instance before calling the delegate if loading failed.

Target is Local Player Save Game

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| class | Save Game Class |  |
| object | Local Player Controller |  |
| string | Slot Name |  |
| delegate | Delegate |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Asynchronously loads a save game object in the specified slot for the local player, if this returns true the delegate will get called later.False means the load was never scheduled, otherwise it will create and initialize a new instance before calling the delegate if loading failed. |
