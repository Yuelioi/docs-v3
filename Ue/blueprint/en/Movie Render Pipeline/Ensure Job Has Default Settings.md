---
display_name: Ensure Job Has Default Settings
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Ensure the job has the settings specified by the project settings added. If they're already added we don't modify the object so that we don't make it confused about whether or not you've modified the preset.

Target is Movie Pipeline Editor Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Job |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
