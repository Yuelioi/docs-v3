---
display_name: Paste Elements from String
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Typed Element Framework](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementFramework) > [Common](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementFramework/Common)

Paste any elements from the given string
Note: Internally this just calls PasteNormalizedElements on the result of UTypedElementSelectionSet::GetNormalizedSelection.

Target is Typed Element Common Actions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Selection Set |  |
| object | World |  |
| struct | Paste Option |  |
| string | Input String |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | Paste any elements from the given string@note Internally this just calls PasteNormalizedElements on the result of UTypedElementSelectionSet::GetNormalizedSelection. |
