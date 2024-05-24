---
display_name: Get Slot Transform from Request Result
order: 24
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Returns the transform (in world space) of the slot associated to the given RequestResult.

Target is Smart Object Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Request Result | Result returned by any of the Find Smart Object(s) methods. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Out Slot Transform | Transform (in world space) of the slot associated to the RequestResult. |
| boolean | Return Value | Whether the transform was found and assigned to 'OutSlotTransform' |
