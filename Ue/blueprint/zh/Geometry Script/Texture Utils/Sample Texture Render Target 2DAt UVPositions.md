---
title: Sample Texture Render Target 2DAt UVPositions
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Texture Utils](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/TextureUtils)

Sample the the given TextureMap at the list of UV positions and return the color at each position in ColorList output.
This function fetches GPU data before sampling so, depending on your application, it can be inefficient and slow!

Target is Geometry Script Library Texture Map Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | UVList |  |
| object | Texture |  |
| struct | Sample Options |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Color List |  |
