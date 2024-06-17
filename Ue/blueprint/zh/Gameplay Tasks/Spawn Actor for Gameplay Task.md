---
title: Spawn Actor for Gameplay Task
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Gameplay Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GameplayTasks)

Spawn new Actor on the network authority (server)

Target is Gameplay Task Spawn Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Task Owner |  |
| vector | Spawn Location |  |
| rotator | Spawn Rotation |  |
| class | Class |  |
| boolean | Spawn Only on Authority |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | Success |  |
| exec | Did Not Spawn | Called when we can't spawn: on clients or potentially on server if they fail to spawn (rare) |
| object | Spawned Actor |  |
