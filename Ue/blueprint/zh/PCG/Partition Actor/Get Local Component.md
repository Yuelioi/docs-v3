---
display_name: Get Local Component
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [PCG](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PCG) > [Partition Actor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PCG/PartitionActor)

TODO: Make this in-editor only; during runtime, we should keep a map of component to bounds/volume only
and preferably precompute the intersection, so this would make it easier/possible to not have the original actor in game version.

Target is PCGPartition Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| object | Original Component |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | TODO: Make this in-editor only; during runtime, we should keep a map of component to bounds/volume onlyand preferably precompute the intersection, so this would make it easier/possible to not have the original actor in game version. |
