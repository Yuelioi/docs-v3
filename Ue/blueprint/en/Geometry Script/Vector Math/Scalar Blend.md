---
title: Scalar Blend
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Vector Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/VectorMath)

Compute (ConstantA  *A) + (ConstantB*  B) for each pair of values in ScalarListA and ScalarListB and return in new ScalarList.
By default (constants = 1) this just adds the two values. Set ConstantB = -1 to subtract B from A.
Can also be used to Linear Interpolate, by setting ConstantB = (1-ConstantA)

Target is Geometry Script Library Vector Math Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Scalar List A |  |
| struct | Scalar List B |  |
| real | Constant A |  |
| real | Constant B |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | Compute (ConstantA  *A) + (ConstantB*  B) for each pair of values in ScalarListA and ScalarListB and return in new ScalarList.By default (constants = 1) this just adds the two values. Set ConstantB = -1 to subtract B from A.Can also be used to Linear Interpolate, by setting ConstantB = (1-ConstantA) |
