---
title: Build String (LinearColor)
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [String](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/String)

Converts a color->string, creating a new string in the form AppendTo+Prefix+InColor+Suffix

Target is Kismet String Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| string | Append To | An existing string to use as the start of the conversion string |
| string | Prefix | A string to use as a prefix, after the AppendTo string |
| linearcolor | In Color | The linear color value to convert. Uses the standard ToString conversion |
| string | Suffix | A suffix to append to the end of the conversion string |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Return Value | A new string built from the passed parameters |
