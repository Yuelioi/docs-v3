---
title: Add Controller Roll Input
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Pawn](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Pawn) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Pawn/Input)

Add input (affecting Roll) to the Controller's ControlRotation, if it is a local PlayerController.
This value is multiplied by the PlayerController's InputRollScale value.

Target is Pawn

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Val | Amount to add to Roll. This value is multiplied by the PlayerController's InputRollScale value. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
