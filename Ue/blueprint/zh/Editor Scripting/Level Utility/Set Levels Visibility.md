---
title: Set Levels Visibility
order: 61
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Level Utility](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/LevelUtility)

Sets a level's visibility in the editor. More efficient than SetLevelsVisibility when changing the visibility of multiple levels simultaneously.

Target is Editor Level Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Levels | The levels to modify. |
| boolean | Should be Visible | The level's new visibility state for each level. |
| boolean | Force Layers Visible | If true and the level is visible, force the level's layers to be visible. |
| enum | Modify Mode | ELevelVisibilityDirtyMode mode value. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
