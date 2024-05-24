---
display_name: Mark Smart Object Slot as Free
order: 39
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Marks a claimed or occupied smart object as free.

Target is Smart Object Blueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Claim Handle | Handle to a claimed slot returned by any of the Claim methods. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Success | Whether the claim was successfully released or not |
