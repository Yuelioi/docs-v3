---
display_name: Get Parent Element
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Typed Element Interfaces](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementInterfaces) > [Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TypedElementInterfaces/Hierarchy)

Get the logical parent of this element, if any.
eg) A component might return its actor, or a static mesh instance might return its ISM component.

Target is Typed Element Hierarchy Interface

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| struct | In Element Handle |  |
| boolean | Allow Create |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | Get the logical parent of this element, if any.eg) A component might return its actor, or a static mesh instance might return its ISM component. |
