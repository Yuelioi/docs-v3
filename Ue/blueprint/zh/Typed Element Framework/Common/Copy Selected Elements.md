---
display_name: Copy Selected Elements
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Typed Element Framework](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementFramework) > [Common](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementFramework/Common)

Copy any elements from the given selection set that can be copied into the clipboard
Note: Internally this just calls CopyNormalizedElements on the result of UTypedElementSelectionSet::GetNormalizedSelection.

Target is Typed Element Common Actions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Selection Set |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Copy any elements from the given selection set that can be copied into the clipboard@note Internally this just calls CopyNormalizedElements on the result of UTypedElementSelectionSet::GetNormalizedSelection. |
