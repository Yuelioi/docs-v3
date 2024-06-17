---
title: Async Load Game from Slot
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Save Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SaveGame)

Schedule an async load of a specific slot. UGameplayStatics::AsyncLoadGameFromSlot is the native version of this.
When the load has succeeded or failed, the completed pin is activated with success/failure and the newly loaded save game object if valid.
Keep in mind that some platforms may not support trying to load and save at the same time.

Target is Async Action Handle Save Game

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Slot Name | Name of the save game slot to load from. |
| integer | User Index | The platform user index that identifies the user doing the saving, ignored on some platforms. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | Completed | Delegate called when the save/load completes |
| object | Save Game |  |
| boolean | Success |  |
