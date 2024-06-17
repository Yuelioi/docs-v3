---
title: Get Instance Transforms
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD) > [Foliage Exporter](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD/FoliageExporter)

Returns the transforms of all instances of a particular UFoliageType on a given level. If no level is provided all instances will be returned.
Use GetUsedFoliageTypes() to retrieve all foliage types managed by a particular actor.

Target is Usd Conversion Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Actor |  |
| object | Foliage Type |  |
| object | Instances Level |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| transform | Return Value | Returns the transforms of all instances of a particular UFoliageType on a given level. If no level is provided all instances will be returned.Use GetUsedFoliageTypes() to retrieve all foliage types managed by a particular actor. |
