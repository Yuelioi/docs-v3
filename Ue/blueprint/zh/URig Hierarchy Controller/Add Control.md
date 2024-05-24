---
display_name: Add Control
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy Controller](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchyController)

Adds a control to the hierarchy

Target is Rig Hierarchy Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Name | The suggested name of the new animation channel - will eventually be corrected by the namespace |
| struct | In Parent Control | The parent of the new animation channel. |
| struct | In Settings | All of the animation channel's settings |
| boolean | Setup Undo | If set to true the stack will record the change for undo / redo |
| boolean | Print Python Command |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | The key for the newly created animation channel. |
