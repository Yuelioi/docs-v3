---
title: Create Actor
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dataprep](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Dataprep) > [Editing Operation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Dataprep/EditingOperation)

Add an actor to the Dataprep's transient world and action's working set

Target is Dataprep Editing Operation

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| class | Actor Class | Class of the actor to create |
| string | Actor Name | Name of the actor to create. Name collision will be performed before naming the asset |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The actor newly created |
