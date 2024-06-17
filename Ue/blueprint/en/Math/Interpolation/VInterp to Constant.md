---
title: VInterp to Constant
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Interpolation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Interpolation)

Tries to reach Target at a constant rate.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Current | Actual position |
| vector | Target | Target position |
| real | Delta Time | Time since last tick |
| real | Interp Speed | Interpolation speed |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value | New interpolated position |
