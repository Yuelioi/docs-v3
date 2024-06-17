---
title: Get Actors from Layers
order: 20
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Layers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Layers)

Gets all the actors associated with ANY of the specified layers. Analog to AppendActorsFromLayers but it returns rather than appends the actors.

Target is Layers Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | Layer Names | The layers to find actors for. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | The list to assign the found actors to. |
