---
title: Set Level Viewport Camera Info
order: 26
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Development](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Development) > [Editor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Development/Editor)

Sets information about the camera position for the primary level editor viewport.
In the UnrealEd module instead of Level Editor as it uses FLevelEditorViewportClient which is in this module

Target is Unreal Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | Camera Location | Location the camera will be moved to. |
| rotator | Camera Rotation | Rotation the camera will be set to. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
