---
display_name: Add Value to Projector Range
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Customizable Object Instance](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/CustomizableObjectInstance)

Increases the range of values of the projector with ParamName, returns the index of the new projector value, -1 otherwise.
The added value is initialized with the default projector as set up in the editor and is the last one of the range.

Target is Customizable Object Instance

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Param Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value | Increases the range of values of the projector with ParamName, returns the index of the new projector value, -1 otherwise.The added value is initialized with the default projector as set up in the editor and is the last one of the range. |
