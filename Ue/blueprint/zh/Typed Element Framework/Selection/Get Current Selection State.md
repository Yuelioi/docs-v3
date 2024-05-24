---
display_name: Get Current Selection State
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Typed Element Framework](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementFramework) > [Selection](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementFramework/Selection)

Serializes the current selection set.
The calling code is responsible for storing any state information. The selection set can be returned to a prior state using RestoreSelectionState.

Target is Typed Element Selection Set

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | the current state of the selection set. |
