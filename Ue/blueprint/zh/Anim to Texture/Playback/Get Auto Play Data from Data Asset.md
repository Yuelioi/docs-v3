---
title: Get Auto Play Data from Data Asset
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Anim to Texture](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AnimtoTexture) > [Playback](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AnimtoTexture/Playback)

Returns an AutoPlayData with the Start and End Frame for the given AnimationIndex.
If AnimationIndex is out of range, false will be returned.

Target is Anim to Texture Instance Playback Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Data Asset |  |
| integer | Animation Index |  |
| real | Time Offset |  |
| real | Play Rate |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Auto Play Data |  |
| boolean | Return Value | Returns an AutoPlayData with the Start and End Frame for the given AnimationIndex.If AnimationIndex is out of range, false will be returned. |
