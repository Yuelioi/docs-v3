---
title: Set Consumed
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Set the job to be consumed. A consumed job is disabled in the UI and should not be
submitted for rendering again. This allows jobs to be added to a queue, the queue
submitted to a remote farm (consume the jobs) and then more jobs to be added and
the second submission to the farm won't re-submit the already in-progress jobs.

Jobs can be unconsumed when the render finishes to re-enable editing.

For C++ implementations override `virtual void SetConsumed_Implementation() override`
For Python/BP implementations override
@unreal.ufunction(override=True)
def set_consumed(self, isConsumed):

Target is Movie Pipeline Executor Job

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | In Consumed | True if the job should be consumed and disabled for editing in the UI. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
