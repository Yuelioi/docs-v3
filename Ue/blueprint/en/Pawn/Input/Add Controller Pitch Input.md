---
title: Add Controller Pitch Input
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Pawn](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Pawn) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Pawn/Input)

Add input (affecting Pitch) to the Controller's ControlRotation, if it is a local PlayerController.
This value is multiplied by the PlayerController's InputPitchScale value.

Target is Pawn

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Val | Amount to add to Pitch. This value is multiplied by the PlayerController's InputPitchScale value. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
