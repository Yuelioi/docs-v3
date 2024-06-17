---
title: Find Smart Objects
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Blueprint function for spatial lookup for slot candidates respecting request criteria and selection conditions.

Target is Smart Object Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Request | Parameters defining the search area and criteria |
| object | User Actor | Actor claiming the smart object |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Results | List of smart object slot candidates |
| boolean | Return Value | All valid smart objects in range. |
