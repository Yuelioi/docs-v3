---
title: Get RPMRange
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Moto Synth](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MotoSynth)

Retrieves RPM range of the moto synth, taking into account the acceleration and deceleration sources. The min RPM is the largest of the min RPms of either and the max RPM is min of the max RPMs of either.

Target is Synth Component Moto

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Out Min RPM |  |
| real | Out Max RPM |  |
