---
title: Start Continuous Input Injection for Action (Message)
order: 26
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input)

Starts simulation of input via injection. This injects the given input every tick until it is stopped with StopContinuousInputInjectionForAction.

Target is Enhanced Input Subsystem Interface

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Action | The Input Action to set inject input for |
| struct | Raw Value | The value to set the action to (the type will be controlled by the Action) |
| object | Modifiers | The modifiers to apply to the injected input. |
| object | Triggers | The triggers to apply to the injected input. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
