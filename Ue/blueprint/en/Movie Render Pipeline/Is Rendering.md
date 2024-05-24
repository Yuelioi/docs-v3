---
display_name: Is Rendering
order: 73
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Report the current state of the executor. This is used to know if we can call Execute again.

For C++ implementations override `virtual bool IsRendering_Implementation() const override`
For Python/BP implementations override
@unreal.ufunction(override=True)
def is_rendering(self):
return ?

Target is Movie Pipeline Executor Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | True if the executor is currently working on a queue to produce a render. |
