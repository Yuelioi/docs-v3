---
display_name: Try Move to Slide Along Surface
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mover](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Mover)

Attempts to move a component along a surface. Returns the percent of time applied, with 0.0 meaning no movement occurred.

Target is Movement Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Updated Component |  |
| object | Updated Primitive |  |
| object | Mover Component |  |
| vector | Delta |  |
| real | Pct Of Delta to Move |  |
| struct | Rotation |  |
| vector | Normal |  |
| boolean | Handle Impact |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Hit |  |
| struct | Move Record |  |
| real | Return Value | Attempts to move a component along a surface. Returns the percent of time applied, with 0.0 meaning no movement occurred. |
