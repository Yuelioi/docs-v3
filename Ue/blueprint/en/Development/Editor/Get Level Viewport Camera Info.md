---
title: Get Level Viewport Camera Info
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Development](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Development) > [Editor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Development/Editor)

Gets information about the camera position for the primary level editor viewport. In non-editor builds, these will be zeroed
In the UnrealEd module instead of Level Editor as it uses FLevelEditorViewportClient which is in this module

Target is Unreal Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Camera Location | (out) Current location of the level editing viewport camera, or zero if none found |
| rotator | Camera Rotation | (out) Current rotation of the level editing viewport camera, or zero if none found |
| boolean | Return Value | Whether or not we were able to get a camera for a level editing viewport |
