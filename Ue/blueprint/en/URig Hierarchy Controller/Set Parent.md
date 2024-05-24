---
display_name: Set Parent
order: 32
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy Controller](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchyController)

Sets a new parent to an element. For elements that allow more than one parent the parent list will be replaced.

Target is Rig Hierarchy Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Child | The key of the element to set the parent for |
| struct | In Parent | The key of the new parent to set |
| boolean | Maintain Global Transform | If set to true the child will stay in the same place spatially, otherwise it will maintain it's local transform (and potential move). |
| boolean | Setup Undo | If set to true the stack will record the change for undo / redo |
| boolean | Print Python Command | If set to true a python command equivalent to this call will be printed out |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Returns true if successful. |
