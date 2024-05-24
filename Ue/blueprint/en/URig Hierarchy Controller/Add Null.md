---
display_name: Add Null
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy Controller](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchyController)

Adds a null to the hierarchy

Target is Rig Hierarchy Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Name | The suggested name of the new null - will eventually be corrected by the namespace |
| struct | In Parent | The (optional) parent of the new null. If you don't need a parent, pass FRigElementKey() |
| transform | In Transform | The transform for the new null - either in local or global null, based on bTransformInGlobal |
| boolean | Transform in Global | Set this to true if the Transform passed is expressed in global null, false for local null. |
| boolean | Setup Undo | If set to true the stack will record the change for undo / redo |
| boolean | Print Python Command | If set to true a python command equivalent to this call will be printed out |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | The key for the newly created null. |
