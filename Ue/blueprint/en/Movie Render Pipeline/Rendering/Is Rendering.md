---
display_name: Is Rendering
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline/Rendering)

Returns true if there is an active executor working on producing a movie. This could be actively rendering frames,
or working on post processing (finalizing file writes, etc.). Use GetActiveExecutor() and query it directly for
more information, progress updates, etc.

Target is MoviePipeline Runtime Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Returns true if there is an active executor working on producing a movie. This could be actively rendering frames,or working on post processing (finalizing file writes, etc.). Use GetActiveExecutor() and query it directly formore information, progress updates, etc. |
