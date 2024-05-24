---
display_name: Load Level
order: 30
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Level Utility](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/LevelUtility)

Close the current Persistent Level (without saving it). Loads the specified level.

Target is Level Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Asset Path | Asset Path of the level to be loaded. ie. /Game/MyFolder/MyAsset |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the operation succeeds. |
