---
title: Set Attached Stage Actor
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD) > [Stage Actor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD/StageActor)

Sets which actor is currently attached to the USD Stage Editor.
Provide None/nullptr to clear the attached stage actor.

Target is Usd Stage Editor Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | New Actor | The actor to select |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True in case the new actor was attached to the USD Stage Editor. |
