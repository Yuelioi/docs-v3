---
title: Inject Input Vector for Action
order: 25
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input)

Input simulation via injection. Runs modifiers and triggers delegates as if the input had come through the underlying input system as FKeys.
Applies action modifiers and triggers on top.

Target is Enhanced Input Subsystem Interface

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| object | Action | The Input Action to set inject input for |
| vector | Value | The value to set the action to (the type will be controlled by the Action) |
| object | Modifiers | The modifiers to apply to the injected input. |
| object | Triggers | The triggers to apply to the injected input. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
