---
display_name: Is Consumed
order: 68
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Gets whether or not the job has been marked as being consumed. A consumed job is not editable
in the UI and should not be submitted for rendering as it is either already finished or
already in progress.

For C++ implementations override `virtual bool IsConsumed_Implementation() override`
For Python/BP implementations override
@unreal.ufunction(override=True)
def is_consumed(self):
return ?

Target is Movie Pipeline Executor Job

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Gets whether or not the job has been marked as being consumed. A consumed job is not editablein the UI and should not be submitted for rendering as it is either already finished oralready in progress.For C++ implementations override `virtual bool IsConsumed_Implementation() override`For Python/BP implementations override@unreal.ufunction(override=True)def is_consumed(self):return ? |
