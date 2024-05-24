---
display_name: Build String (Boolean)
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [String](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/String)

Converts a boolean->string, creating a new string in the form AppendTo+Prefix+InBool+Suffix

Target is Kismet String Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| string | Append To | An existing string to use as the start of the conversion string |
| string | Prefix | A string to use as a prefix, after the AppendTo string |
| boolean | In Bool | The bool value to convert. Will add "true" or "false" to the conversion string |
| string | Suffix | A suffix to append to the end of the conversion string |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Return Value | A new string built from the passed parameters |
