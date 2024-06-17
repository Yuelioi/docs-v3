---
title: Prestream Textures
order: 69
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering)

Calls PrestreamTextures() for all the actor's meshcomponents.

Target is Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Seconds | Number of seconds to force all mip-levels to be resident |
| boolean | Enable Streaming | Whether to start (true) or stop (false) streaming |
| integer | Cinematic Texture Groups | Bitfield indicating which texture groups that use extra high-resolution mips |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
