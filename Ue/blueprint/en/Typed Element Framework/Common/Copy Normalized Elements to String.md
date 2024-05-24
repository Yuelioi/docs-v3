---
display_name: Copy Normalized Elements to String
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Typed Element Framework](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementFramework) > [Common](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementFramework/Common)

- Copy any elements from the given selection set that can be copied into the clipboard.
- Note: This list should have been pre-normalized via UTypedElementSelectionSet::GetNormalizedSelection or UTypedElementSelectionSet::GetNormalizedElementList.

Target is Typed Element Common Actions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Element List |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Output String |  |
| boolean | Return Value | *Copy any elements from the given selection set that can be copied into the clipboard.* @note This list should have been pre-normalized via UTypedElementSelectionSet::GetNormalizedSelection or UTypedElementSelectionSet::GetNormalizedElementList. |
