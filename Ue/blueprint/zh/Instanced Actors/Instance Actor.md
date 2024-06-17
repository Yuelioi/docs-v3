---
title: Instance Actor
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Instanced Actors](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/InstancedActors)

Adds an instance of ActorClass at InstanceTransform location by spawning or reusing a AInstancedActorsManager at InstanceTransform's grid cell location.
See: UInstancedActorsProjectSettings::GridSize

Target is Instanced Actors Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| class | Actor Class |  |
| transform | Instance Transform |  |
| object | Level |  |
| struct | Instance Tags |  |
| class | Manager Class |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | Adds an instance of ActorClass at InstanceTransform location by spawning or reusing a AInstancedActorsManager at InstanceTransform's grid cell location.@see UInstancedActorsProjectSettings::GridSize |
