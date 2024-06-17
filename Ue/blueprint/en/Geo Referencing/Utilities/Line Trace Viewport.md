---
title: Line Trace Viewport
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geo Referencing](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeoReferencing) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeoReferencing/Utilities)

LineTrace under mouse cursor and return various information

Target is Geo Referencing Editor BPLibrary

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Actors to Ignore | Collection of actors for this trace to ignore. |
| boolean | Trace Complex |  |
| boolean | Show Trace |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector2d struct | Screen Location | Viewport-Space position of cursor. |
| boolean | Success |  |
| struct | Hit Result | The trace hits result. |
