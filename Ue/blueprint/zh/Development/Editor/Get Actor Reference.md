---
title: Get Actor Reference
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Development](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Development) > [Editor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Development/Editor)

Attempts to find the actor specified by PathToActor in the current editor world

Target is Editor Actor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| string | Path to Actor | The path to the actor (e.g. PersistentLevel.PlayerStart) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | A reference to the actor, or none if it wasn't found |
