---
title: Get Transform and Forward Vector
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Interactor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Interactor)

Creates a hand transform and forward vector for a laser pointer for a given hand

Target is Viewport Interactor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Out Hand Transform | The created hand transform |
| vector | Out Forward Vector | The forward vector of the hand |
| boolean | Return Value | True if we have motion controller data for this hand and could return a valid result |
