---
title: Get Configuration
order: 24
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Gets the configuration for the job. This configuration is either standalone (not associated with any preset), or
contains a copy of the preset origin plus any modifications made on top of it. If the preset that this
configuration was originally based on no longer exists, this configuration will still be valid.
See: GetPresetOrigin()

Target is Movie Pipeline Executor Job

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | Gets the configuration for the job. This configuration is either standalone (not associated with any preset), orcontains a copy of the preset origin plus any modifications made on top of it. If the preset that thisconfiguration was originally based on no longer exists, this configuration will still be valid.@see GetPresetOrigin() |
