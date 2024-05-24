---
display_name: Parse Command Line
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities)

- Parses the given string into loose tokens, switches (arguments that begin with - or /) and parameters (-mySwitch=myVar)

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | In Cmd Line | The the string to parse (ie '-foo -bar=/game/baz testtoken' ) * |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Out Tokens |  |
| string | Out Switches |  |
| string | Out Params |  |
