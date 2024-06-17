---
title: Find Substring
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [String](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/String)

Finds the starting index of a substring in the a specified string

Target is Kismet String Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| string | Search In | The string to search within |
| string | Substring | The string to look for in the SearchIn string |
| boolean | Use Case | Whether or not to be case-sensitive |
| boolean | Search from End | Whether or not to start the search from the end of the string instead of the beginning |
| integer | Start Position | The position to start the search from |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Return Value | The index (starting from 0 if bSearchFromEnd is false) of the first occurence of the substring |
