---
title: Get Captured Attribute Magnitude
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Gameplay Effect](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/GameplayEffect)

Gets the captured magnitude value for the given Attribute
For this to work correctly, the Attribute needs to be added to the Relevant Attributes to Capture array

Target is Gameplay Mod Magnitude Calculation

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Effect Spec | The Gameplay Effect Spec to get the info from |
| struct | Attribute | The attribute to query |
| struct | Source Tags |  |
| struct | Target Tags |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Return Value | The magnitude value if found, zero otherwise |
