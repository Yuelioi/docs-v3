---
title: Is Queue Dirty
order: 71
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Returns true if the current queue has been modified since it was loaded, else returns false. Note that the empty
queue that is in use upon the initial load of MRQ is not considered dirty.

Target is Movie Pipeline Queue Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Returns true if the current queue has been modified since it was loaded, else returns false. Note that the emptyqueue that is in use upon the initial load of MRQ is not considered dirty. |
