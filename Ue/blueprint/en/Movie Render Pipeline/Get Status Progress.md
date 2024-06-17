---
title: Get Status Progress
order: 61
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Get the current progress as last set by SetStatusProgress. 0 by default.

For C++ implementations override `virtual float GetStatusProgress_Implementation() override`
For Python/BP implementations override
@unreal.ufunction(override=True)
def get_status_progress(self):
return ?

Target is Movie Pipeline Executor Job

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | Get the current progress as last set by SetStatusProgress. 0 by default.For C++ implementations override `virtual float GetStatusProgress_Implementation() override`For Python/BP implementations override@unreal.ufunction(override=True)def get_status_progress(self):return ? |
