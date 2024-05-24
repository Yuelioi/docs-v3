---
display_name: Set Control Value
order: 138
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Sets a control's current value given its key

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Key | The key of the element to set the current value for |
| struct | In Value | The value to set on the control |
| enum | In Value Type | The type of value to set |
| boolean | Setup Undo | If true the transform stack will be setup for undo / redo |
| boolean | Print Python Commands |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
