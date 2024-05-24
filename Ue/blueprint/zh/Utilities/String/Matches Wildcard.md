---
display_name: Matches Wildcard
order: 31
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [String](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/String)

Searches this string for a given wild card

Target is Kismet String Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| string | Source String |  |
| string | Wildcard | \*?-type wildcard |
| enum | Search Case | Indicates whether the search is case sensitive or not ( defaults to ESearchCase::IgnoreCase ) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | true if this string matches the \*?-type wildcard given. |
