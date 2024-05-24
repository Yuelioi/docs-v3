---
display_name: Set Selection from List
order: 28
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Typed Element Framework](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementFramework) > [Selection](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementFramework/Selection)

Attempt to make the selection the given elements.
Note: Equivalent to calling ClearSelection then SelectElements, but happens in a single batch.

Target is Typed Element Selection Set Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Selection Set |  |
| struct | Element List |  |
| struct | Selection Options |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the selection was changed, false otherwise. |
