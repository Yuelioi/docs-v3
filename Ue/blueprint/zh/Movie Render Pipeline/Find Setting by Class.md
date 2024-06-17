---
title: Find Setting by Class
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Find a setting of a particular type for this config.

Target is Movie Pipeline Config Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| class | In Class | Class that you wish to find the setting object for. |
| boolean | Include Disabled Settings | if true, disabled settings will be included in the search |
| boolean | Exact Match | if true, only exact matches of the specified class will be found, otherwise subclasses of the specified class will also be found |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | An instance of this class if it already exists as a setting on this config, otherwise null. |
