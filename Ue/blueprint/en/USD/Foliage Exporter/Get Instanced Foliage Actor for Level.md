---
display_name: Get Instanced Foliage Actor for Level
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD) > [Foliage Exporter](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD/FoliageExporter)

Wraps AInstancedFoliageActor::GetInstancedFoliageActorForLevel, and allows retrieving the current AInstancedFoliageActor
for a level. Will default to the current editor level if Level is left nullptr.
This function is useful because it's difficult to retrieve this actor otherwise, as it will be filtered from
the results of functions like EditorLevelLibrary.get_all_level_actors()

Target is Usd Conversion Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| boolean | Create if None |  |
| object | Level |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Wraps AInstancedFoliageActor::GetInstancedFoliageActorForLevel, and allows retrieving the current AInstancedFoliageActorfor a level. Will default to the current editor level if Level is left nullptr.This function is useful because it's difficult to retrieve this actor otherwise, as it will be filtered fromthe results of functions like EditorLevelLibrary.get_all_level_actors() |
