---
display_name: Duplicate Normalized Elements
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Typed Element Framework](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementFramework) > [Common](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementFramework/Common)

Duplicate any elements from the given list that can be duplicated.
Note: This list should have been pre-normalized via UTypedElementSelectionSet::GetNormalizedSelection or UTypedElementSelectionSet::GetNormalizedElementList.

Target is Typed Element Common Actions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Element List |  |
| object | World |  |
| vector | Location Offset |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | Duplicate any elements from the given list that can be duplicated.@note This list should have been pre-normalized via UTypedElementSelectionSet::GetNormalizedSelection or UTypedElementSelectionSet::GetNormalizedElementList. |
