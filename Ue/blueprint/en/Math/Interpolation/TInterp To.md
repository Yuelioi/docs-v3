---
title: TInterp To
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Interpolation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Interpolation)

Tries to reach Target transform based on distance from Current position, giving a nice smooth feeling when tracking a position.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Current | Actual transform |
| transform | Target | Target transform |
| real | Delta Time | Time since last tick |
| real | Interp Speed | Interpolation speed, if the speed given is 0, then jump to the target. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Return Value | New interpolated transform |
