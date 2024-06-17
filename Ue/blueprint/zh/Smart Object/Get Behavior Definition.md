---
title: Get Behavior Definition
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Return the behavior definition of a given type from a claimed object.

Target is Smart Object Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Claim Handle | Handle to a claimed slot returned by any of the Claim methods. |
| class | Definition Class | The type of behavior definition. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The base class pointer of the requested behavior definition class associated to the slotClaim handle |
