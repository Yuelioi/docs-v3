---
display_name: Allocate New Job
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline) > [Queue](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline/Queue)

Allocates a new Job in this Queue. The Queue owns the jobs for memory management purposes,
and this will handle that for you.

Target is Movie Pipeline Queue

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| class | In Job Type | Specify the specific Job type that should be created. Custom Executors can use custom Job types to allow the user to provide more information. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The created Executor job instance. |
