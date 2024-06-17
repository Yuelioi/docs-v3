---
title: Move Selected Actors to Level
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Level Creation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/LevelCreation)

Moves the currently selected actors to the specified streaming level. The new actors will be selected

Target is Editor Level Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Dest Level |  |
| boolean | Warn About References | Whether or not to show a modal warning about referenced actors that may no longer function after being moved |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value | The number of actors that were successfully moved to the new level |
