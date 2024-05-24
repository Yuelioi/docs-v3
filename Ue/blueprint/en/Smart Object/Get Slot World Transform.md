---
display_name: Get Slot World Transform
order: 26
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Returns the transform (in world space) of the given slot index.

Target is Smart Object Definition

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| integer | Slot Index | Index within the list of slots. |
| transform | Owner Transform | Transform (in world space) of the slot owner. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Return Value | Transform (in world space) of the slot associated to SlotIndex, or OwnerTransform if index is invalid. |
