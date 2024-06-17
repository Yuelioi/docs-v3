---
title: Get Initialization Time Offset
order: 41
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

The offset that should be applied to the GetInitializationTime() when generating
the {time} related filename tokens. GetInitializationTime() is in UTC so this is
either zero (if you called SetInitializationTime) or your offset from UTC.

Target is Movie Pipeline

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The offset that should be applied to the GetInitializationTime() when generatingthe {time} related filename tokens. GetInitializationTime() is in UTC so this iseither zero (if you called SetInitializationTime) or your offset from UTC. |
