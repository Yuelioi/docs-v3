---
title: Set Layer Color
order: 31
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sprite](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sprite)

Sets the per-layer color multiplier for a specific layer (multiplied with the tile map color and passed to the material as a vertex color)
Note: This will only work on components that own their own tile map (OwnsTileMap returns true), you cannot modify standalone tile map assets

Target is Paper Tile Map Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| linearcolor | New Color |  |
| integer | Layer |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
