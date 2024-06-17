---
title: Find Smart Objects in Actor
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Search a given Actor for slot candidates respecting the request criteria and selection conditions.

Target is Smart Object Blueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Filter | Parameters defining the search area and criteria |
| object | Search Actor | The actor to search |
| object | User Actor | Used to create additional data that could be provided to bind values in the conditions evaluation context |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Results | List of smart object slot candidates found in range |
| boolean | Success | True if at least one candidate was found. |
