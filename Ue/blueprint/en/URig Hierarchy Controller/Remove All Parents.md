---
display_name: Remove All Parents
order: 23
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy Controller](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchyController)

Removes all parents from an element in the hierarchy.

Target is Rig Hierarchy Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Child | The key of the element to remove all parents for |
| boolean | Maintain Global Transform | If set to true the child will stay in the same place spatially, otherwise it will maintain it's local transform (and potential move). |
| boolean | Setup Undo | If set to true the stack will record the change for undo / redo |
| boolean | Print Python Command | If set to true a python command equivalent to this call will be printed out |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Returns true if successful. |
