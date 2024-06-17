---
title: Spawn VPTransient Editor Tickable Actor
order: 26
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Virtual Production](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VirtualProduction)

Spawn an editor-only transient virtual production tickable actor
Note: Actors based on the transient AVPTransientEditorTickableActorBase will NOT be saved in the level.
Note: Being transient also means that transactions happening on them will NOT be replicated on other connected multi-user machines

Target is VPUtilities Editor Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Context Object |  |
| class | Actor Class |  |
| vector | Location |  |
| rotator | Rotation |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Spawn an editor-only transient virtual production tickable actor@note Actors based on the transient AVPTransientEditorTickableActorBase will NOT be saved in the level.@note Being transient also means that transactions happening on them will NOT be replicated on other connected multi-user machines |
