---
display_name: Set Initialization Time
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Override the time this movie pipeline was initialized at. This can be used for render farms
to ensure that jobs on all machines use the same date/time instead of each calculating it locally.
Clears the auto-calculated InitializationTimeOffset, meaning time tokens will be written in UTC.

Needs to be called after ::Initialize(...)

Target is Movie Pipeline

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Date Time | Expected to be in UTC timezone. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
