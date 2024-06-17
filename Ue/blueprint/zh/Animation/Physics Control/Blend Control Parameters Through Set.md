---
title: Blend Control Parameters Through Set
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/PhysicsControl)

Adds an Parameters to the output parameters for each control name in the supplied set. The values in each Parameters will be a linear interpolation of the two supplied Parameters, blending from the start Parameters to the end Parameters across the elements in the set.

Target is Physics Control BPLibrary

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Parameters |  |
| struct | Start Parameters |  |
| struct | End Parameters |  |
| name | Control Names |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Out Parameters |  |
