---
display_name: Add Hit Box
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [HUD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/HUD)

Add a hitbox to the hud

Target is HUD

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector2d struct | Position | Coordinates of the top left of the hit box. |
| vector2d struct | Size | Size of the hit box. |
| name | In Name |  |
| boolean | Consumes Input | Whether click processing should continue if this hit box is clicked. |
| integer | Priority | The priority of the box used for layering. Larger values are considered first. Equal values are considered in the order they were added. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
