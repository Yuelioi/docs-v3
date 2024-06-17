---
title: Get Transform Child Curve Identifier
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Curves](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Curves)

Converts a valid FAnimationCurveIdentifier instance with RCT_Transform curve type to target a child curve.

Target is Animation Curve Identifier Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | In Out Identifier | \[out\] Identifier to be converted |
| enum | Channel | Channel to target |
| enum | Axis | Axis within channel to target |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Valid FAnimationCurveIdentifier if the operation was successful |
