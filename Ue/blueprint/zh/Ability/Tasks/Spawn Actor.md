---
title: Spawn Actor
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Spawn new Actor on the network authority (server)

Target is Ability Task Spawn Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Target Data |  |
| class | Class |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | Success |  |
| exec | Did Not Spawn | Called when we can't spawn: on clients or potentially on server if they fail to spawn (rare) |
| object | Spawned Actor |  |
