---
title: Split
order: 45
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [String](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/String)

Splits this string at given string position case sensitive.

Target is Kismet String Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| string | Source String |  |
| string | In Str | The string to search and split at |
| enum | Search Case | Indicates whether the search is case sensitive or not ( defaults to ESearchCase::IgnoreCase ) |
| enum | Search Dir | Indicates whether the search starts at the begining or at the end ( defaults to ESearchDir::FromStart ) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Left S | out the string to the left of InStr, not updated if return is false |
| string | Right S | out the string to the right of InStr, not updated if return is false |
| boolean | Return Value | true if string is split, otherwise false |
