---
display_name: Resolve Filename Format Arguments
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Resolves the provided InFormatString by converting {format_strings} into settings provided by the primary config.

Target is Movie Pipeline Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | In Format String | A format string (in the form of "{format_key1}\_{format_key2}") to resolve. |
| struct | In Params | The parameters to resolve the format string with. See FMoviePipelineFilenameResolveParams properties for details. Expected that you fill out all of the parameters so that they can be used to resolve strings, otherwise default values may be used. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Out Final Path | The final filepath based on a combination of the format string and the Resolve Params. |
| struct | Out Merged Format Args |  |
