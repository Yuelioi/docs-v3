---
title: Retriggerable Delay
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Flow Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/FlowControl)

Perform a latent action with a retriggerable delay (specified in seconds). Calling again while it is counting down will reset the countdown to Duration.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| real | Duration | length of delay (in seconds). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Completed |  |
