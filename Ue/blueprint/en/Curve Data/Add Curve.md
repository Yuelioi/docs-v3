---
display_name: Add Curve
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Curve Data](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/CurveData)

Adds a new curve with the provided information. Broadcasts a EAnimDataModelNotifyType::CurveAdded notify if successful.

Target is Animation Data Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| struct | Curve Id | Identifier for the to-be-added curve |
| integer | Curve Flags | Flags to be set for the curve |
| boolean | Should Transact | Whether or not any undo-redo changes should be generated |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Whether or not the curve was successfully added |
