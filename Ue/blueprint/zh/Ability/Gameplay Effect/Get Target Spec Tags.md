---
title: Get Target Spec Tags
order: 29
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Gameplay Effect](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/GameplayEffect)

Returns the target spec tags from a Gameplay Effect Spec
Useful for Modifier Magnitude Calculations

Target is Gameplay Mod Magnitude Calculation

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Effect Spec | The Gameplay Effect Spec to get the info from |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Gameplay Tag Container with the copied tags. The container will be empty if no captured source tags exist. |
