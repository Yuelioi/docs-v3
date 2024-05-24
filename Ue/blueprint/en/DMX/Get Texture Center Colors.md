---
display_name: Get Texture Center Colors
order: 54
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [DMX](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DMX)

Reads pixel color in the middle of each "Texture" and output linear colors.
Note, this function locks the GPU to read the color and is slow to call, even if Update TextureResource is not enabled.

Target is DMXFixture Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Texture Atlas |  |
| integer | Num Textures |  |
| boolean | Update Texture Resource |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| linearcolor | Return Value | Reads pixel color in the middle of each "Texture" and output linear colors.Note, this function locks the GPU to read the color and is slow to call, even if Update TextureResource is not enabled. |
