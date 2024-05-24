---
display_name: Load Game from Slot
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Save Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SaveGame)

Load the contents from a given slot.

Target is Gameplay Statics

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
| object | Return Value | Object containing loaded game state (nullptr if load fails) |
