---
display_name: Remove Level From World
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Level Creation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/LevelCreation)

Removes given level from the world. Note, this will only work for sub-levels in the main level.

Target is Editor Level Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Level | Level asset to remove from the world. |
| boolean | Clear Selection | If true, it will clear the editor selection. |
| boolean | Reset Transaction Buffer | If true, it will reset the transaction buffer (i.e. clear undo history) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the level was successfully removed. |
