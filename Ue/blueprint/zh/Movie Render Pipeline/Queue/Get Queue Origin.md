---
title: Get Queue Origin
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline) > [Queue](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline/Queue)

Gets the queue that this queue was originally based on (if any). The origin will only be set on transient
queues; the origin will be nullptr for non-transient queues because the origin will be this object.

Target is Movie Pipeline Queue

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | Gets the queue that this queue was originally based on (if any). The origin will only be set on transientqueues; the origin will be nullptr for non-transient queues because the origin will be this object. |
