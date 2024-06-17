---
title: Remove Actor from Data Layer
order: 30
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Data Layers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DataLayers)

Removes an actor from the specified DataLayer.

Target is Data Layer Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Actor | The actor to remove from the provided DataLayer |
| object | Data Layer to Remove | The DataLayer to remove the actor from |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the actor was removed from the DataLayer. false is returned if the actor already belonged to the DataLayer. |
