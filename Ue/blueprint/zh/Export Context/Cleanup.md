---
display_name: Cleanup
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Export Context](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ExportContext)

Discards the currently opened stage. This is critical when using this class via scripting: The C++ destructor will
not be called when the python object runs out of scope, so we would otherwise keep a strong reference to the stage

Target is Usd Conversion Blueprint Context

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
