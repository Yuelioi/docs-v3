---
display_name: Get Gameplay Attribute Value
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Gameplay Attributes](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GameplayAttributes)

Returns the current value of the given gameplay attribute, or zero if the attribute is not found.
NOTE: This doesn't take predicted gameplay effect modifiers into consideration, so the value may not be accurate on clients at all times.

Target is Ability System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Attribute | The gameplay attribute to query |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Found | Set to true if the attribute exists in this component |
| real | Return Value |  |
