---
title: Resolve Filename Format Arguments
order: 66
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Graph](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieGraph)

Takes a Movie Graph format string (in the form of {token}), a list of parameters (which normally come from the running UMovieGraphPipeline) and
resolves them into a string. Unknown tokens are ignored. Which tokens can be resolved depends on the contents of InParams, tokens from settings
rely on a evaluated config being provided, etc.

Target is Movie Graph Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | In Format String | Format string to attempt to resolve. Leave blank if just the format args should be populated. |
| struct | In Params | A list of parameters to use as source data for the resolve step. Normally comes from the UMovieGraphPipeline instance, - but takes (mostly) POD here to allow using this function outside of the render runtime. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Merged Format Args | The set of KVP for both filename formats and file metadata that is generated as a result of this. Provided in case you - needed to do your own string resolving with the final dataset. |
| string | Return Value | The resolved format string. Returns an empty string if InFormatString is blank. |
