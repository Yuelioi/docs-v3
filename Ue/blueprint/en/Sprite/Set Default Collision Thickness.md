---
display_name: Set Default Collision Thickness
order: 28
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sprite](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sprite)

Sets the default thickness for any layers that don't override the collision thickness
Note: This will only work on components that own their own tile map (OwnsTileMap returns true), you cannot modify standalone tile map assets

Target is Paper Tile Map Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Thickness |  |
| boolean | Rebuild Collision |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
