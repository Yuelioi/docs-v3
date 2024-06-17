---
title: Set Input Mode Game And UI
order: 23
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input)

Setup an input mode that allows only the UI to respond to user input, and if the UI doesn't handle it player input / player controller gets a chance.

Note: This means that any bound Input events in the widget will be called.

Target is Widget Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Player Controller |  |
| object | In Widget to Focus |  |
| enum | In Mouse Lock Mode |  |
| boolean | Hide Cursor During Capture |  |
| boolean | Flush Input |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
