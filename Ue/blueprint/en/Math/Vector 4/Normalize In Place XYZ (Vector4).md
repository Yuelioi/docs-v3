---
title: Normalize In Place XYZ (Vector4)
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Vector 4](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Vector4)

Normalize this vector in-place if it is large enough or set it to (0,0,0,0) otherwise. The W element is ignored and the returned vector has W=0.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | A |  |
| real | Tolerance | Minimum squared length of vector for normalization. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
