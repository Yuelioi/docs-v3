---
display_name: Add Parent
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy Controller](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchyController)

Adds a new parent to an element. For elements that allow only one parent the parent will be replaced (Same as ::SetParent).

Target is Rig Hierarchy Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Child | The key of the element to add the parent for |
| struct | In Parent | The key of the new parent to add |
| real | In Weight | The initial weight to give to the parent |
| boolean | Maintain Global Transform | If set to true the child will stay in the same place spatially, otherwise it will maintain it's local transform (and potential move). |
| boolean | Setup Undo | If set to true the stack will record the change for undo / redo |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Returns true if successful. |
