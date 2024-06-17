---
title: Set Deferred Collision Updates Enabled
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dynamic Mesh Component](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DynamicMeshComponent)

Set value of bDeferCollisionUpdates, when enabled, collision is not automatically recomputed each time the mesh changes.

Target is Dynamic Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Enabled |  |
| boolean | Immediate Update | if true, UpdateCollision(true) is called if bEnabled=false, ie to force a collision rebuild |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
