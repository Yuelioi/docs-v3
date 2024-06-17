---
title: Find Smart Objects in Targeting Request
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Search the results of the given targeting handle request for smart objects that match the request criteria

Target is Smart Object Blueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Filter | Parameters defining the search area and criteria |
| struct | Targeting Handle | The targeting handle of the request that will have its results searched for smart objects |
| object | User Actor | Used to create additional data that could be provided to bind values in the conditions evaluation context |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Results | List of smart object slot candidates found in range |
| boolean | Success | True if at least one candidate was found. |
