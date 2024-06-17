---
title: Get or Create Variable Overrides
order: 64
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

This method will return you the object which contains variable overrides for the Primary Graph assigned to this job. You need to provide
a pointer to the exact graph you want (as the Primary Graph may contain sub-graphs, and those sub-graphs can have their own variables),
though this will be the same as GetGraphPreset() if you're not using any sub-graphs, or your variables only exist on the Primary graph.

If you want to override a variable on the primary graph but only for a specific shot, you should get the UMoviePipelineExecutorShot and
call that classes version of this function, except passing True for the extra boolean. See comment on that function for more details.

Target is Movie Pipeline Executor Job

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Graph | The graph asset to get the Job Override values for. Should be the graph the variables you want to edit are defined on, which can either be the primary graph (GetGraphPreset()) or one of the sub-graphs it points to (as sub-graphs can contain their own variables which are all shown at the top level job in the Editor UI). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | A container object which holds a copy of the variables for the specified Graph Asset that can be used to override their values on jobs without actually editing the default asset. |
