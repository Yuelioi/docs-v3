---
title: Get Object Classification at Location
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AR Augmented Reality](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality) > [Classification](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ARAugmentedReality/Classification)

Try to determine the classification of the object at a world space location
@InWorldLocation: the world location where the classification is needed
@OutClassification: the classification result
@OutClassificationLocation: the world location at where the classification is calculated
@MaxLocationDiff: the max distance between the specified world location and the classification location

Target is ARMesh Geometry

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | In World Location |  |
| real | Max Location Diff |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| enum | Out Classification |  |
| vector | Out Classification Location |  |
| boolean | Return Value | : whether a valid classification result is calculated |
