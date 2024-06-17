---
title: Spawn Decal at Location
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering) > [Decal](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering/Decal)

Spawns a decal at the given location and rotation, fire and forget. Does not replicate.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Decal Material | decal's material |
| vector | Decal Size | size of decal |
| vector | Location | location to place the decal in world space |
| rotator | Rotation | rotation to place the decal in world space |
| real | Life Span | destroy decal component after time runs out (0 = infinite) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |
