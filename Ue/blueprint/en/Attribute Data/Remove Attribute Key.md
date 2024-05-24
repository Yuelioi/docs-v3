---
display_name: Remove Attribute Key
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Attribute Data](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AttributeData)

Remove a single key from the attribute with provided identifier. Broadcasts a EAnimDataModelNotifyType::AttributeChanged notify if successful.

Target is Animation Data Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| struct | Attribute Identifier | Identifier for the attribute from which the key is to be removed |
| real | Time | Time of the key to be removed |
| boolean | Should Transact | Whether or not any undo-redo changes should be generated |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Whether or not the attribute key was successfully removed |
