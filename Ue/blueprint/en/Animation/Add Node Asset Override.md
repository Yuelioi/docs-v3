---
title: Add Node Asset Override
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation)

Adds an Animation Asset override for the provided AnimationBlueprint, replacing any instance of Target with Override

Target is Animation Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Anim Blueprint | The Animation Blueprint to add/set the Override for |
| object | Target | The Animation Asset to add an override for (overrides all instances of the asset) |
| object | Override | The Animation Asset to used to override the Target with (types have to match) |
| boolean | Print Applied Overrides | Flag whether or not to print the applied overrides |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
