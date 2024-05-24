---
display_name: Set Status Message
order: 25
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Set the status of this shot to the given value. This will be shown on the UI if progress
is set to a value less than zero. If progress is > 0 then the progress bar will be shown
on the UI instead. Progress and Status Message are cosmetic.

For C++ implementations override `virtual void SetStatusMessage_Implementation() override`
For Python/BP implementations override
@unreal.ufunction(override=True)
def set_status_message(self, inStatus):

Target is Movie Pipeline Executor Shot

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | In Status | The status message you wish the executor to have. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
