---
title: Ease
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Interpolation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Interpolation)

Interpolates from value A to value B using a user specified easing function

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| enum | Function | EEasingFunc Enum FunctionSpecifies the desired ease function to be applied. If connected no customization is possible. |
| real | Alpha | Float (double-precision) AlphaAlpha value used to specify the easing in time. |
| wildcard | A | Wildcard AEasing start value |
| wildcard | B | Wildcard BEasing end value |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| wildcard | Result | Wildcard ResultEasing result value |
