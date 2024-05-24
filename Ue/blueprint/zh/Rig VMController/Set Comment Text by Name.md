---
display_name: Set Comment Text by Name
order: 101
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rig VMController](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RigVMController)

Sets the comment text and properties of a comment node in the graph by name.
This causes a CommentTextChanged modified event.

Target is Rig VMController

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Node Name |  |
| string | In Comment Text |  |
| integer | In Comment Font Size |  |
| boolean | In Comment Bubble Visible |  |
| boolean | In Comment Color Bubble |  |
| boolean | Setup Undo Redo |  |
| boolean | Print Python Command |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Sets the comment text and properties of a comment node in the graph by name.This causes a CommentTextChanged modified event. |
