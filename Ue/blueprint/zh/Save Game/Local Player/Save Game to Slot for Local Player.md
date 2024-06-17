---
title: Save Game to Slot for Local Player
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Save Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SaveGame) > [Local Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SaveGame/LocalPlayer)

Synchronously save using the slot and user index, stalling the main thread until it completes.
This will return true if the save was requested, and errors should be handled by the HandlePostSave function that will be called immediately.

Target is Local Player Save Game

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Synchronously save using the slot and user index, stalling the main thread until it completes.This will return true if the save was requested, and errors should be handled by the HandlePostSave function that will be called immediately. |
