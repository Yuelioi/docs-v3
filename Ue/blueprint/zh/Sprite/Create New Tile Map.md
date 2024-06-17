---
title: Create New Tile Map
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sprite](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sprite)

Creates a new tile map of the specified size, replacing the TileMap reference (or dropping the previous owned one)

Target is Paper Tile Map Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Map Width | Width of the map (in tiles) |
| integer | Map Height | Height of the map (in tiles) |
| integer | Tile Width | Width of one tile (in pixels) |
| integer | Tile Height | Height of one tile (in pixels) |
| real | Pixels Per Unreal Unit |  |
| boolean | Create Layer | Should an empty layer be created? |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
