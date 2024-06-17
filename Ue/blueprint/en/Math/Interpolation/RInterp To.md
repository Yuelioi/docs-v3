---
title: RInterp To
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Interpolation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Interpolation)

Tries to reach Target rotation based on Current rotation, giving a nice smooth feeling when rotating to Target rotation.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| rotator | Current | Actual rotation |
| rotator | Target | Target rotation |
| real | Delta Time | Time since last tick |
| real | Interp Speed | Interpolation speed, if the speed given is 0, then jump to the target. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| rotator | Return Value | New interpolated position |
