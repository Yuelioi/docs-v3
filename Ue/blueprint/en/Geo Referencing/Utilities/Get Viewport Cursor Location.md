---
title: Get Viewport Cursor Location
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geo Referencing](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeoReferencing) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeoReferencing/Utilities)

Retrieve the Viewport-Space position of the mouse in the Level Editor Viewport. If the Level editor not are in focus it will return false.

Target is Geo Referencing Editor BPLibrary

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Focused | If the Level editor not are in focus it will return false. |
| vector2d struct | Screen Location | The screen location result. |
