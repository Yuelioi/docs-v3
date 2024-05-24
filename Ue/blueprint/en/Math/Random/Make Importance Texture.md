---
display_name: Make Importance Texture
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Random](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Random)

Create an FImportanceTexture object for texture-driven importance sampling from a 2D RGBA8 texture

Target is Importance Sampling Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Texture | Texture object to use. Must be RGBA8 format. |
| enum | Weighting Func | How to turn the texture data into probability weights |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | new ImportanceTexture object for use with ImportanceSample |
