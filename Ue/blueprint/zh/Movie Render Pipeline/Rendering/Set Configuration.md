---
title: Set Configuration
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline/Rendering)

Sets some advanced configuration options that are used only occasionally to have better control over integrating it into
your game/application. This applies to both RenderQueueWithExecutor(Instance) and the simplified RenderJob API. This persists
until you call it again with different settings, and needs to be called before the Render\* functions.

Target is MoviePipeline Runtime Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| class | In Progress Widget Class |  |
| boolean | Render Player Viewport | If true, we will render the regular player viewport in addition to the off-screen MRQ render. This is significantly performance heavy (doubles render times) but can be useful in the event that you want to keep rendering the player viewport to better integrate the render into your own application. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
