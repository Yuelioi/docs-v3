---
display_name: Finalize
order: 29
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [FXConverter Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/FXConverterUtilities)

Apply all pending UNiagaraScriptConversionContexts and UNiagaraRendererProperties to the owned
UNiagaraEmitterContexts by creating clipboard inputs and pasting them onto the emitter conversion context's
Emitter.
Afterwards compile the system so the changes take effect.

Target is Niagara System Conversion Context

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
