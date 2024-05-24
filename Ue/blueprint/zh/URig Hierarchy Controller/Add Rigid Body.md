---
display_name: Add Rigid Body
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy Controller](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchyController)

Adds a rigidbody to the hierarchy

Target is Rig Hierarchy Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Name | The suggested name of the new rigidbody - will eventually be corrected by the namespace |
| struct | In Parent | The (optional) parent of the new rigidbody. If you don't need a parent, pass FRigElementKey() |
| struct | In Settings | All of the rigidbody's settings |
| transform | In Local Transform | The transform for the new rigidbody - in the space of the provided parent |
| boolean | Setup Undo | If set to true the stack will record the change for undo / redo |
| boolean | Print Python Command | If set to true a python command equivalent to this call will be printed out |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | The key for the newly created rigidbody. |
