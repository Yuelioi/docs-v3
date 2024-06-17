---
title: Make Brush from Material
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Widget](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Widget) > [Brush](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Widget/Brush)

Creates a Slate Brush from a Material. Materials don't have an implicit size, so providing a widget and height
is required to hint slate with how large the image wants to be by default.

Target is Widget Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Material |  |
| integer | Width |  |
| integer | Height |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | A new slate brush using the material. |
