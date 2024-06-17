---
title: Render Queue with Executor
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline/Rendering)

Starts processing the current queue with the supplied executor class. This starts an async process which
may or may not run in a separate process (or on separate machines), determined by the executor implementation.
The executor should report progress for jobs depending on the implementation.

Target is MoviePipeline Runtime Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| class | In Executor Type | A subclass of UMoviePipelineExecutorBase. An instance of this class is created and started. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | A pointer to the instance of the class created. This instance will be kept alive by the Queue Subsystem until it has finished (or been canceled). Register for progress reports and various callbacks on this instance. |
