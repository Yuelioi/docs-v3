---
display_name: Find or Add Setting by Class
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Finds a setting of a particular type for this pipeline config, adding it if it doesn't already exist.

Target is Movie Pipeline Config Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| class | In Class | Class you wish to find or create the setting object for. |
| boolean | Include Disabled Settings | if true, disabled settings will be included in the search |
| boolean | Exact Match | if true, only exact matches of the specified class will be found, otherwise subclasses of the specified class will also be found |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | An instance of this class as a setting on this config. |
