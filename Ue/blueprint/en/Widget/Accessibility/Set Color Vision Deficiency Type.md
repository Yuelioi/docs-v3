---
title: Set Color Vision Deficiency Type
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Widget](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Widget) > [Accessibility](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Widget/Accessibility)

Apply color deficiency correction settings to the game window

Target is Widget Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| enum | Type | The type of color deficiency correction to apply. |
| real | Severity | Intensity of the color deficiency correction effect, from 0 to 1. |
| boolean | Correct Deficiency | Shifts the color spectrum to the visible range based on the current deficiency type. |
| boolean | Show Correction with Deficiency | If you're correcting the color deficiency, you can use this to visualize what the correction looks like with the deficiency. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
