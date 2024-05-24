---
display_name: Create New Streaming Level
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Level Creation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/LevelCreation)

Creates a new streaming level in the current world

Target is Editor Level Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| class | Level Streaming Class | The streaming class type instead to use for the level. |
| string | New Level Path | Optional path to the level package path format ("e.g /Game/MyLevel"). If empty, the user will be prompted during the save process. |
| boolean | Move Selected Actors Into New Level | If true, move any selected actors into the new level. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Returns the newly created level, or NULL on failure |
