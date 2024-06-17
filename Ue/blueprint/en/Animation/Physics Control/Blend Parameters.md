---
title: Blend Parameters
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/PhysicsControl)

Returns the linear interpolation of two sets of parameter Parameters. Any Parameters that exists in one of the input sets but not the other will be added to the output with a weight of 1.

Target is Physics Control BPLibrary

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | From Parameters |  |
| struct | To Parameters |  |
| real | Weight |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Parameters |  |
