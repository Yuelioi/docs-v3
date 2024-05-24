---
display_name: Add Level to World
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Level Creation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/LevelCreation)

Adds the named level package to the world. Does nothing if the level already exists in the world.

Target is Editor Level Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | World |  |
| string | Level Package Name | The package name ("e.g /Game/MyLevel") of the level package to add. |
| class | Level Streaming Class | The streaming class type to use for the level. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The new level, or NULL if the level couldn't added. |
