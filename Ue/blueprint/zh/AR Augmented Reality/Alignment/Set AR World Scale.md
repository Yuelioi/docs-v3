---
title: Set AR World Scale
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AR Augmented Reality](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality) > [Alignment](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality/Alignment)

Helper function that modifies the alignment transform scale so that virtual content in the world space appears to be "scaled".
Note that ultimately the scaling effect is achieved through modifying the translation of the camera:
moving the camera further away from the origin makes objects appear to be smaller, and vice versa.

Target is ARBlueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| real | In World Scale |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
