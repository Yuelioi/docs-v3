---
display_name: Set Control Shape Transform
order: 136
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Sets the shape transform for a given control element by key

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Key | The key of the control element to set the shape transform for |
| transform | In Transform | The new shape transform value to set |
| boolean | Initial | If true the initial value will be used |
| boolean | Setup Undo | If true the transform stack will be setup for undo / redo |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
