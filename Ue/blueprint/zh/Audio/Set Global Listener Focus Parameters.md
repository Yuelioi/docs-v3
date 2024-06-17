---
title: Set Global Listener Focus Parameters
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio)

Sets the global listener focus parameters, which will scale focus behavior of sounds based on their focus azimuth
settings in their attenuation settings.

- Fire and Forget.
- Not Replicated.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| real | Focus Azimuth Scale | An angle scale value used to scale the azimuth angle that defines where sounds are in-focus. |
| real | Non Focus Azimuth Scale |  |
| real | Focus Distance Scale | A distance scale value to use for sounds which are in-focus. Values \< 1.0 will reduce perceived distance to sounds, values > 1.0 will increase perceived distance to in-focus sounds. |
| real | Non Focus Distance Scale | A distance scale value to use for sounds which are out-of-focus. Values \< 1.0 will reduce perceived distance to sounds, values > 1.0 will increase perceived distance to in-focus sounds. |
| real | Focus Volume Scale |  |
| real | Non Focus Volume Scale |  |
| real | Focus Priority Scale | A priority scale value (> 0.0) to use for sounds which are in-focus. Values \< 1.0 will reduce the priority of in-focus sounds, values > 1.0 will increase the priority of in-focus sounds. |
| real | Non Focus Priority Scale | A priority scale value (> 0.0) to use for sounds which are out-of-focus. Values \< 1.0 will reduce the priority of sounds out-of-focus sounds, values > 1.0 will increase the priority of out-of-focus sounds. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
