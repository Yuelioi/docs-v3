---
title: Apply Color Space Transform
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Open Color IO](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/OpenColorIO)

Applies a rendering pass of the color transform described in the settings

Target is Open Color IOBlueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Conversion Settings | Settings describing the color space transform to apply |
| object | Input Texture | Texture in the source color space |
| object | Output Render Target | RenderTarget where to draw the input texture in the destination color space |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if a rendering command to apply the transform was queued. |
