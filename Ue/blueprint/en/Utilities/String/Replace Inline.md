---
title: Replace Inline
order: 36
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [String](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/String)

Replace all occurrences of SearchText with ReplacementText in this string.

Target is Kismet String Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Source String |  |
| string | Search Text | the text that should be removed from this string |
| string | Replacement Text | the text to insert in its place |
| enum | Search Case | Indicates whether the search is case sensitive or not ( defaults to ESearchCase::IgnoreCase ) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value | the number of occurrences of SearchText that were replaced. |
