---
title: Possess
order: 24
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Pawn](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Pawn)

Handles attaching this controller to the specified pawn.
Only runs on the network authority (where HasAuthority() returns true).
Derived native classes can override OnPossess to filter the specified pawn.
When possessed pawn changed, blueprint class gets notified by ReceivePossess
and OnNewPawn delegate is broadcasted.

Target is Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Pawn | The Pawn to be possessed. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
