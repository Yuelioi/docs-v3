---
display_name: Set Parameter Mapping
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Compositing Pass](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/CompositingPass)

Set the parameter mappings between texture parameters and composure layers. Users can not create new entries into the map as the keys are read only.
Invalid Texture parameter names will result in a failed setting operation.

Target is Compositing Element Material Pass

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Texture Param Name | The name of the texture parameter inside the material interface. Used as key. |
| name | Composure Layer Name | The name of the composure layer the texture parameter is mapped to. Used as value. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | bool True if set operation is successful. |
