---
title: Set Layer Collision
order: 30
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sprite](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sprite)

Sets the collision thickness for a specific layer
Note: This will only work on components that own their own tile map (OwnsTileMap returns true), you cannot modify standalone tile map assets

Target is Paper Tile Map Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Layer |  |
| boolean | Has Collision |  |
| boolean | Override Thickness |  |
| real | Custom Thickness |  |
| boolean | Override Offset |  |
| real | Custom Offset |  |
| boolean | Rebuild Collision |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
