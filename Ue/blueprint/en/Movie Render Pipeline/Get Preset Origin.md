---
display_name: Get Preset Origin
order: 53
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Gets the preset for this job, but only if the preset has not been modified. If it has been modified, or the preset
no longer exists, returns nullptr.
See: GetConfiguration()

Target is Movie Pipeline Executor Job

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | Gets the preset for this job, but only if the preset has not been modified. If it has been modified, or the presetno longer exists, returns nullptr.@see GetConfiguration() |
