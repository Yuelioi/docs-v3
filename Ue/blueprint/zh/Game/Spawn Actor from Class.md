---
title: Spawn Actor from Class
order: 51
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game)

Attempts to spawn a new Actor with the specified transform

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| class | Class | Actor Class Reference ClassThe object class you want to construct |
| transform | Spawn Transform | The transform to spawn the Actor with |
| enum | Collision Handling Override | Specifies how to handle collisions at the spawn point. If undefined, uses actor class settings. |
| enum | Transform Scale Method |  |
| object | Owner | Can be left empty; primarily used for replication (bNetUseOwnerRelevancy and bOnlyRelevantToOwner), or visibility (PrimitiveComponent's bOwnerNoSee/bOnlyOwnerSee) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Actor Object Reference Return ValueThe constructed object |
