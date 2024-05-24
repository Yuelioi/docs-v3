---
display_name: On Duplicated
order: 79
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Should be called to clear status and user data after duplication so that jobs stay
unique and don't pick up ids or other unwanted behavior from the pareant job.

For C++ implementations override `virtual bool OnDuplicated_Implementation() override`
For Python/BP implementations override
@unreal.ufunction(override=True)
def on_duplicated(self):

Target is Movie Pipeline Executor Job

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
