---
title: Set Graph Preset
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Sets the graph-style preset that this job will use. Note that this will cause the graph to switch over to using
graph-style configuration if it is not already using it.

Target is Movie Pipeline Executor Job

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Graph Preset | The graph preset to assign to the job. |
| boolean | Update Variable Assignments | Set to false if variable assignments should NOT be automatically updated to reflect the graph preset being used. This is normally not what you want and should be used with caution. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
