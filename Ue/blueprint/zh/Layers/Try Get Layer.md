---
display_name: Try Get Layer
order: 42
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Layers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Layers)

Attempts to get the ULayer Object of the provided layer name.

Target is Layers Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Layer Name | The name of the layer whose ULayer Object to retrieve |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out Layer |  |
| boolean | Return Value | If true a valid ULayer Object was found and set to OutLayer; if false, a valid ULayer object was not found and invalid set to OutLayer |
