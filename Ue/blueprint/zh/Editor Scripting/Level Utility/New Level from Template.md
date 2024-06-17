---
title: New Level from Template
order: 31
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Level Utility](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/LevelUtility)

Close the current Persistent Level (without saving it). Create a new Level base on another level and save it. Load the new created level.

Target is Level Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Asset Path | Asset Path of where the level will be saved. ie. /Game/MyFolder/MyAsset |
| string | Template Asset Path | Level to be used as Template. ie. /Game/MyFolder/MyAsset |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the operation succeeds. |
