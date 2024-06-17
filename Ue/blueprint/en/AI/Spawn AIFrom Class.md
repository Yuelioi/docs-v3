---
title: Spawn AIFrom Class
order: 32
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI)

Spawns AI agent of a given class. The PawnClass needs to have AIController
set for the function to spawn a controller as well.

Target is AIBlueprint Helper Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| class | Pawn Class |  |
| object | Behavior Tree | if set, and the function has successfully spawned and AI controller, this BehaviorTree asset will be assigned to the AI controller, and run. |
| vector | Location |  |
| rotator | Rotation |  |
| boolean | No Collision Fail |  |
| object | Owner | lets you spawn the AI in a sublevel rather than in the persistent level (which is the default behavior). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |
