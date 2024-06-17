---
title: Get Config Origin
order: 23
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Gets the config that this config was originally based on (if any). The origin will only be set on transient
configs; the origin will be nullptr for non-transient configs because the origin will be this object.

Target is Movie Pipeline Config Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | Gets the config that this config was originally based on (if any). The origin will only be set on transientconfigs; the origin will be nullptr for non-transient configs because the origin will be this object. |
