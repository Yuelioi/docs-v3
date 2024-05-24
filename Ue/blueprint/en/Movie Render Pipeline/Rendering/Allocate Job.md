---
display_name: Allocate Job
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline/Rendering)

Convenience function for creating a UMoviePipelineExecutorJob out of the given Level Sequence asset. The
newly created job will be initialized to render on the current level, and will not have any default settings
added to it - instead you will need to call FindOrAddSettingByClass on the job's configuration to add
settings such as render passes (UMoviePipelineDeferredPassBase), output types (UMoviePipelineImageSequenceOutput_PNG),
and configure the output directory (UMoviePipelineOutputSetting). Once configuration is complete, register
a delegate to OnRenderFinished and then call RenderJob.

Calling this function will clear the internal queue, see RenderJob for more details.

Using this function while IsRendering() returns true will result in an exception being thrown and no attempt
being made to create the job.

Target is MoviePipeline Runtime Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Sequence |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Convenience function for creating a UMoviePipelineExecutorJob out of the given Level Sequence asset. Thenewly created job will be initialized to render on the current level, and will not have any default settingsadded to it - instead you will need to call FindOrAddSettingByClass on the job's configuration to addsettings such as render passes (UMoviePipelineDeferredPassBase), output types (UMoviePipelineImageSequenceOutput_PNG),and configure the output directory (UMoviePipelineOutputSetting). Once configuration is complete, registera delegate to OnRenderFinished and then call RenderJob.Calling this function will clear the internal queue, see RenderJob for more details.Using this function while IsRendering() returns true will result in an exception being thrown and no attemptbeing made to create the job. |
