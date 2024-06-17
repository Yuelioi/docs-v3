---
title: Set Is Enabled
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Set the job to be enabled/disabled. This is exposed to the user in the Queue UI
so they can disable a job after loading a queue to skip trying to run it.

For C++ implementations override `virtual void SetIsEnabled_Implementation() override`
For Python/BP implementations override
@unreal.ufunction(override=True)
def set_is_enabled(self, isEnabled):

Target is Movie Pipeline Executor Job

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | In Enabled | True if the job should be enabled and rendered. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
