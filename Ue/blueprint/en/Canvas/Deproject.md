---
title: Deproject
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Canvas](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Canvas)

Performs a deprojection of a screen space coordinate using the projection matrix set up for the Canvas.

Target is Canvas

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector2d struct | Screen Position | Screen space position to deproject to the World. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | World Origin | Vector which is the world position of the screen space position. |
| vector | World Direction | Vector which can be used in a trace to determine what is "behind" the screen space position. Useful for object picking. |
