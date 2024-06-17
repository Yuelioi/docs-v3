---
title: Draw Lines
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Painting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Painting)

Draws several line segments.

Target is Widget Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Context |  |
| vector2d struct | Points | Line pairs, each line needs to be 2 separate points in the array. |
| linearcolor | Tint | Color to render the line. |
| boolean | Anti Alias | Whether the line should be antialiased. |
| real | Thickness | How many pixels thick this line should be. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
