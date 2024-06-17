---
title: Async Save Game to Slot for Local Player
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Save Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SaveGame) > [Local Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SaveGame/LocalPlayer)

Asynchronously save to the slot and user index.
This will return true if the save was requested, and errors should be handled by the HandlePostSave function after the save succeeds or fails

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
| boolean | Return Value | Asynchronously save to the slot and user index.This will return true if the save was requested, and errors should be handled by the HandlePostSave function after the save succeeds or fails |
