---
title: Get Gameplay Ability from Spec Handle
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Gameplay Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/GameplayAbility)

Provides the Gameplay Ability object associated with an Ability Spec Handle
This can be either an instanced ability, or in the case of shared abilities, the Class Default Object

Target is Ability System Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Ability System |  |
| struct | Ability Spec Handle |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Is Instance | Set to true if this is an instanced ability instead of a shared CDO |
| object | Return Value | Pointer to the Gameplay Ability object |
