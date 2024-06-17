---
title: Set Force Mip Levels to be Resident
order: 44
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering) > [Material](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering/Material)

Force the streaming system to disregard the normal logic for the specified duration and
instead always load all mip-levels for all textures used by this material.

Target is Material Interface

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Override Force Miplevels to be Resident | Whether to use (true) or ignore (false) the bForceMiplevelsToBeResidentValue parameter. |
| boolean | Force Miplevels to be Resident Value | true forces all mips to stream in. false lets other factors decide what to do with the mips. |
| real | Force Duration | Number of seconds to keep all mip-levels in memory, disregarding the normal priority logic. Negative value turns it off. |
| integer | Cinematic Texture Groups | Bitfield indicating texture groups that should use extra high-resolution mips |
| boolean | Fast Response | USE WITH EXTREME CAUTION! Fast response textures incur sizable GT overhead and disturb streaming metric calculation. Avoid whenever possible. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
