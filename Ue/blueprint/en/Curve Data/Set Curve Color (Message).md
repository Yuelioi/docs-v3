---
display_name: Set Curve Color (Message)
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Curve Data](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/CurveData)

Changes the color of the curve with provided identifier. Broadcasts a EAnimDataModelNotifyType::CurveColorChanged notify if successful.
Currently changing curve colors is only supported for float curves.

Target is Animation Data Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Curve Id | Identifier of the curve to change the color for |
| linearcolor | Color | Color to which the curve is to be set |
| boolean | Should Transact | Whether or not any undo-redo changes should be generated |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Whether or not the curve color was successfully changed |
