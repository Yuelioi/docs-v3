---
title: Find Smart Object
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Spatial lookup for first slot in range respecting request criteria and selection conditions.

Target is Smart Object Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Request | Parameters defining the search area and criteria |
| object | User Actor | Actor claiming the smart object used to evaluate selection conditions |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | First valid smart object in range. Not the closest one, just the one that happens to be retrieved first from space partition |
