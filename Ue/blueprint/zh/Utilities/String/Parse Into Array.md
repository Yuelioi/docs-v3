---
display_name: Parse Into Array
order: 35
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [String](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/String)

Gets an array of strings from a source string divided up by a separator and empty strings can optionally be culled.

Target is Kismet String Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| string | Source String | The string to chop up |
| string | Delimiter | The string to delimit on |
| boolean | Cull Empty Strings | = true - Cull (true) empty strings or add them to the array (false) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Return Value | The array of string that have been separated |
