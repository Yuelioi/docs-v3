---
title: Join Static Mesh Actors
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Dataprep](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/Dataprep)

Create a new Actor in the level that contains a duplicate of all the Actors Static Meshes Component.
The ActorsToJoin need to be in the same Level.
This will have a low impact on performance but may help the edition by grouping the meshes under a single Actor.

Target is Static Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Actors to Join | List of Actors to join. |
| struct | Join Options | Options on how to join the actors. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The new created actor. |
