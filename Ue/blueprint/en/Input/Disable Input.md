---
title: Disable Input
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input)

Removes this actor from the stack of input being handled by a PlayerController.

Target is Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Player Controller | The PlayerController whose input events we no longer want to receive. If null, this actor will stop receiving input from all PlayerControllers. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
