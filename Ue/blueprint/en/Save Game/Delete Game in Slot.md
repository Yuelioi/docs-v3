---
display_name: Delete Game in Slot
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Save Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SaveGame)

Delete a save game in a particular slot.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Slot Name | Name of save game slot to delete. |
| integer | User Index | The platform user index that identifies the user doing the saving, ignored on some platforms. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if a file was actually able to be deleted. use DoesSaveGameExist to distinguish between delete failures and failure due to file not existing. |
