---
title: Mark Smart Object Slot as Occupied
order: 40
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Marks a previously claimed smart object slot as occupied.

Target is Smart Object Blueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Claim Handle | Handle to a claimed slot returned by any of the Claim methods. |
| class | Definition Class | The type of behavior definition the user wants to use. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The base class pointer of the requested behavior definition class associated to the slot |
