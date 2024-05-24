---
display_name: Mark Smart Object Slot as Claimed
order: 38
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Marks a smart object slot from a request result as claimed.

Target is Smart Object Blueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Slot Handle | Handle to a smart object slot. |
| object | User Actor | Actor claiming the smart object |
| enum | Claim Priority | Claim priority, a slot claimed at lower priority can be claimed by higher priority (unless already in use). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Claim Handle | A handle binding the claimed smart object, its slot and a user id. |
