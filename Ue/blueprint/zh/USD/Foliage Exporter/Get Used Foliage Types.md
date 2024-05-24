---
display_name: Get Used Foliage Types
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD) > [Foliage Exporter](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD/FoliageExporter)

Returns all the different types of UFoliageType assets that a particular AInstancedFoliageActor uses.
This function exists because we want to retrieve all instances of all foliage types on an actor, but we
can't return nested containers from UFUNCTIONs, so users of this API should call this, and then GetInstanceTransforms.

Target is Usd Conversion Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Actor |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Returns all the different types of UFoliageType assets that a particular AInstancedFoliageActor uses.This function exists because we want to retrieve all instances of all foliage types on an actor, but wecan't return nested containers from UFUNCTIONs, so users of this API should call this, and then GetInstanceTransforms. |
