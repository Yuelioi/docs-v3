---
display_name: Async Save Game to Slot
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Save Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SaveGame)

Schedule an async save to a specific slot. UGameplayStatics::AsyncSaveGameToSlot is the native version of this.
When the save has succeeded or failed, the completed pin is activated with success/failure and the save game object.
Keep in mind that some platforms may not support trying to load and save at the same time.

Target is Async Action Handle Save Game

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Save Game Object | Object that contains data about the save game that we want to write out. |
| string | Slot Name | Name of the save game slot to load from. |
| integer | User Index | The platform user index that identifies the user doing the saving, ignored on some platforms. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | Completed | Delegate called when the save/load completes |
| object | Save Game |  |
| boolean | Success |  |
