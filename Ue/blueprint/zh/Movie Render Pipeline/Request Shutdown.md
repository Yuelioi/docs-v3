---
display_name: Request Shutdown
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Request the movie pipeline to shut down at the next available time. The pipeline will attempt to abandon
the current frame (such as if there are more temporal samples pending) but may be forced into finishing if
there are spatial samples already submitted to the GPU. The shutdown flow will be run to ensure already
completed work is written to disk. This is a non-blocking operation, use Shutdown() instead if you need to
block until it is fully shut down.

Target is Movie Pipeline Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Is Error | Whether this is a request for early shut down due to an error This function is thread safe. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
