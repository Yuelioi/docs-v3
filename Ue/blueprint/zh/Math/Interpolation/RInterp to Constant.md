---
title: RInterp to Constant
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Interpolation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Interpolation)

Tries to reach Target rotation at a constant rate.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| rotator | Current | Actual rotation |
| rotator | Target | Target rotation |
| real | Delta Time | Time since last tick |
| real | Interp Speed | Interpolation speed |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| rotator | Return Value | New interpolated position |
