---
title: Get Azimuth and Elevation
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Vector](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Vector)

Breaks a direction vector apart into Azimuth (Yaw) and Elevation (Pitch) rotation values given in degrees. (non-clamped)
Relative to the provided reference frame (an Actor's WorldTransform for example)

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | In Direction |  |
| transform | Reference Frame |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Azimuth |  |
| real | Elevation |  |
