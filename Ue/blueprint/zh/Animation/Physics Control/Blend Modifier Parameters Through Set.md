---
title: Blend Modifier Parameters Through Set
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/PhysicsControl)

Adds an Parameters to the output parameters for each modifier name in the supplied set. The values in each Parameters will be a linear interpolation of the two supplied Parameters, blending from the start Parameters to the end Parameters across the elements in the set.

Target is Physics Control BPLibrary

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | In Parameters |  |
| struct | In Start Modifier Parameters |  |
| struct | In End Modifier Parameters |  |
| name | Modifier Names |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Parameters |  |
