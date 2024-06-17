---
title: Set Cubemap Blend
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sky Light](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SkyLight)

Creates sky lighting from a blend between two cubemaps, which is only valid when SourceType is set to SpecifiedCubemap.
This can be used to seamlessly transition sky lighting between different times of day.
The caller should continue to update the blend until BlendFraction is 0 or 1 to reduce rendering cost.
The caller is responsible for avoiding pops due to changing the source or destination.

Target is Sky Light Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Source Cubemap |  |
| object | Destination Cubemap |  |
| real | In Blend Fraction |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
