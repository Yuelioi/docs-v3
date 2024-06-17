---
title: Get User Ability Activation Inhibited
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Abilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Abilities)

This is meant to be used to inhibit activating an ability from an input perspective. (E.g., the menu is pulled up, another game mechanism is consuming all input, etc)
This should only be called on locally owned players.
This should not be used to game mechanics like silences or disables. Those should be done through gameplay effects.

Target is Ability System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | This is meant to be used to inhibit activating an ability from an input perspective. (E.g., the menu is pulled up, another game mechanism is consuming all input, etc)This should only be called on locally owned players.This should not be used to game mechanics like silences or disables. Those should be done through gameplay effects. |
