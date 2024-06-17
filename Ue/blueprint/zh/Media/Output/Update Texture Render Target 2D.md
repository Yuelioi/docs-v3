---
title: Update Texture Render Target 2D
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Output](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/Output)

Update the current capture with every frame for a TextureRenderTarget2D.
The TextureRenderTarget2D needs to be of the same size and have the same pixel format as requested by the media output.

Target is Media Capture

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Render Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Return true if the capture was successfully updated. If false is returned, the capture was stopped. |
