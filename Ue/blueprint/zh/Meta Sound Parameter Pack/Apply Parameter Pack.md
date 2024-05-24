---
display_name: Apply Parameter Pack
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Meta Sound Parameter Pack](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MetaSoundParameterPack)

Makes a copy of the supplied parameter pack and passes it to the MetaSoundGenerator
for asynchronous processing. IT ALSO caches this copy so that if the AudioComponent
is virtualized the parameter pack will be sent again when/if the AudioComponent is
"unvirtualized".

Target is Metasound Generator Handle

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Pack |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Makes a copy of the supplied parameter pack and passes it to the MetaSoundGeneratorfor asynchronous processing. IT ALSO caches this copy so that if the AudioComponentis virtualized the parameter pack will be sent again when/if the AudioComponent is"unvirtualized". |
