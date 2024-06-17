---
title: Make UDIMVirtual Texture from Texture 2Ds
order: 30
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities)

Make a UDIM virtual texture from a list of regular 2D textures

Target is UDIMTexture Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Output Path Name | Path name of the UDIM texture (e.g. /Game/MyTexture) |
| object | Source Textures | List of regular 2D textures to be packed into the atlas |
| struct | Block Coords | Coordinates of the corresponding texture in the atlas |
| boolean | Keep Existing Settings | Whether to keep existing settings if a texture with the same path name exists. Otherwise, settings will be copied from the first source texture |
| boolean | Check Out and Save | Whether to check out and save the UDIM texture |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | UTexture2D\* Pointer to the UDIM texture or null if failed |
