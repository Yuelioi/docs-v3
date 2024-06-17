---
title: Remove Actor Instance
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Instanced Actors](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/InstancedActors)

Removes all instance data for InstanceHandle.

This simply adds this instance to a FreeList which incurs extra cost to process at runtime before instance spawning.

Target is Instanced Actors Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Instance Handle | Instance to remove |
| boolean | Destroy Manager if Empty | If true, and InstanceHandle is the last instance in its manager, destroy the now-empty manager. This implicitly clears the FreeList which is stored per-manager. Any subsequent instance adds will then create a fresh manager. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value |  |
