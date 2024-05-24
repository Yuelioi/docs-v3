---
display_name: Shutdown
order: 28
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Abandons any future work on this Movie Pipeline and runs through the shutdown flow to ensure already
completed work is written to disk. This is a blocking-operation and will not return until all outstanding
work has been completed.

Target is Movie Pipeline Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Is Error | Whether this is an early shut down due to an error This function should only be called from the game thread. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
