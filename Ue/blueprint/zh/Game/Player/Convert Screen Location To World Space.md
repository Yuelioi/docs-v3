---
display_name: Convert Screen Location To World Space
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game) > [Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game/Player)

Convert 2D screen position to World Space 3D position and direction. Returns false if unable to determine value. \*

Target is Player Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| real | Screen X |  |
| real | Screen Y |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | World Location |  |
| vector | World Direction |  |
| boolean | Return Value | Convert 2D screen position to World Space 3D position and direction. Returns false if unable to determine value. * |
