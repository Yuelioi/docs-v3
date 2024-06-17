---
title: Get Status Message
order: 60
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Get the current status message for this shot. May be an empty string.

For C++ implementations override `virtual FString GetStatusMessage_Implementation() override`
For Python/BP implementations override
@unreal.ufunction(override=True)
def get_status_message(self):
return ?

Target is Movie Pipeline Executor Shot

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Return Value | Get the current status message for this shot. May be an empty string.For C++ implementations override `virtual FString GetStatusMessage_Implementation() override`For Python/BP implementations override@unreal.ufunction(override=True)def get_status_message(self):return ? |
