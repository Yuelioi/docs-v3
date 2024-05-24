---
display_name: Set Curve Keys
order: 28
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Curve Data](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/CurveData)

Replace the keys for the curve with provided identifier and name. Broadcasts a EAnimDataModelNotifyType::CurveChanged notify if successful.

Target is Animation Data Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| struct | Curve Id | Identifier for the curve for which the keys are to be replaced |
| struct | Curve Keys | Keys with which the existing keys are to be replaced |
| boolean | Should Transact | Whether or not any undo-redo changes should be generated |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Whether or not replacing curve keys was successful |
