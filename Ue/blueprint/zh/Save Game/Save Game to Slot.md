---
display_name: Save Game to Slot
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Save Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SaveGame)

Save the contents of the SaveGameObject to a platform-specific save slot/file.
Note: This will write out all non-transient properties, the SaveGame property flag is not checked

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Save Game Object | Object that contains data about the save game that we want to write out |
| string | Slot Name | Name of save game slot to save to. |
| integer | User Index | The platform user index that identifies the user doing the saving, ignored on some platforms. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Whether we successfully saved this information |
