---
title: Get Gameplay Effect Magnitude
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Gameplay Effects](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GameplayEffects)

Raw accessor to ask the magnitude of a gameplay effect, not necessarily always correct. How should outside code (UI, etc) ask things like 'how much is this gameplay effect modifying my damage by'
(most likely we want to catch this on the backend - when damage is applied we can get a full dump/history of how the number got to where it is. But still we may need polling methods like below (how much would my damage be)

Target is Ability System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Handle |  |
| struct | Attribute |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | Raw accessor to ask the magnitude of a gameplay effect, not necessarily always correct. How should outside code (UI, etc) ask things like 'how much is this gameplay effect modifying my damage by'(most likely we want to catch this on the backend - when damage is applied we can get a full dump/history of how the number got to where it is. But still we may need polling methods like below (how much would my damage be) |
