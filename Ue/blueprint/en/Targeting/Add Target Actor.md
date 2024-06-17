---
title: Add Target Actor
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Targeting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Targeting)

Adds a single Actor to the Targeting Results for a given TargetingRequestHandle.
Returns false when the Actor was already in the list.

NOTE: If you have a HitResult associated with this selection, please use AddHitResult instead.

Target is Simple Targeting Selection Task

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Targeting Handle |  |
| object | Actor |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Adds a single Actor to the Targeting Results for a given TargetingRequestHandle.Returns false when the Actor was already in the list.NOTE: If you have a HitResult associated with this selection, please use AddHitResult instead. |
