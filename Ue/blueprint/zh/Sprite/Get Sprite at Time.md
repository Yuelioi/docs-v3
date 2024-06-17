---
title: Get Sprite at Time
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sprite](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sprite)

Returns the sprite at the specified time (in seconds), or nullptr if none exists.
When bClampToEnds is true, it will choose the first or last sprite if the time is out of range.

Target is Paper Flipbook

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| real | Time |  |
| boolean | Clamp to Ends |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | Returns the sprite at the specified time (in seconds), or nullptr if none exists.When bClampToEnds is true, it will choose the first or last sprite if the time is out of range. |
