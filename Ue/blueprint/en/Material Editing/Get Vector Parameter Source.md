---
display_name: Get Vector Parameter Source
order: 42
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Material Editing](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MaterialEditing)

Returns the path of the asset where the parameter originated, as well as true/false if it was found

Target is Material Editing Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Material | The material or material instance you want to look up a parameter from |
| name | Parameter Name | The parameter name |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Parameter Source | The soft object path of the asset the parameter originates in |
| boolean | Return Value | Whether or not the parameter was found in this material |
