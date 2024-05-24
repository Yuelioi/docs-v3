---
display_name: Make Brush from Texture
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Widget](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Widget) > [Brush](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Widget/Brush)

Creates a Slate Brush from a Texture2D

Target is Widget Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Texture |  |
| integer | Width | When less than or equal to zero, the Width of the brush will default to the Width of the Texture |
| integer | Height | When less than or equal to zero, the Height of the brush will default to the Height of the Texture |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | A new slate brush using the texture. |
