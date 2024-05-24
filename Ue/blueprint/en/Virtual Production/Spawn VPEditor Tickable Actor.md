---
display_name: Spawn VPEditor Tickable Actor
order: 24
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Virtual Production](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VirtualProduction)

Spawn an editor-only virtual production tickable actor
Note: Actors based on the non-transient AVPEditorTickableActorBase will be saved in the level.
Note: Being non-transient also means that transactions happening on them will be replicated on other connected multi-user machines

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
| object | Return Value | Spawn an editor-only virtual production tickable actor@note Actors based on the non-transient AVPEditorTickableActorBase will be saved in the level.@note Being non-transient also means that transactions happening on them will be replicated on other connected multi-user machines |
