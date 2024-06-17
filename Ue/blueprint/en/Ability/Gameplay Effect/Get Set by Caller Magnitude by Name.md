---
title: Get Set by Caller Magnitude by Name
order: 22
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Gameplay Effect](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/GameplayEffect)

Extracts the Set by Caller Magnitude from a Gameplay Effect Spec

Target is Gameplay Mod Magnitude Calculation

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Effect Spec | The Gameplay Effect Spec to get the info from |
| name | Magnitude Name | The effect name to query |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Return Value | The magnitude value if found, zero otherwise |
