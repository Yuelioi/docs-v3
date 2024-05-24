---
display_name: Set Material Texture Param Name
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Lazy Image](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LazyImage)

Establishes the name of the texture parameter on the currently applied brush material to which textures should be applied.
Does nothing if the current brush resource object is not a material.

Note: that this is cleared out automatically if/when a new material is established on the brush.
You must call this function again after doing so if the new material has a texture param.

Target is Common Lazy Image

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Texture Param Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
