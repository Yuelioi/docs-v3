---
display_name: Is Map Valid for Remote Render
order: 70
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Checks to see if any of the Jobs try to point to maps that wouldn't be valid on a remote render (ie: unsaved maps)

Target is Movie Pipeline Editor Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | In Jobs |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Checks to see if any of the Jobs try to point to maps that wouldn't be valid on a remote render (ie: unsaved maps) |
