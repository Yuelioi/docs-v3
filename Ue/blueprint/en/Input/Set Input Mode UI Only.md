---
title: Set Input Mode UI Only
order: 25
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input)

Setup an input mode that allows only the UI to respond to user input.

Note: This means that any bound Input Events in the widget will not be called!

Target is Widget Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Player Controller |  |
| object | In Widget to Focus |  |
| enum | In Mouse Lock Mode |  |
| boolean | Flush Input |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
