---
display_name: Add Reroute Node on Link
order: 22
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rig VMController](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RigVMController)

Adds a Reroute Node on an existing Link to the edited Graph.
Reroute Nodes can be used to visually improve the data flow,
they don't require any additional memory though and are purely
cosmetic. This causes a NodeAdded modified event.

Target is Rig VMController

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Link |  |
| vector2d struct | In Position |  |
| string | In Node Name |  |
| boolean | Setup Undo Redo |  |
| boolean | Print Python Command |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Adds a Reroute Node on an existing Link to the edited Graph.Reroute Nodes can be used to visually improve the data flow,they don't require any additional memory though and are purelycosmetic. This causes a NodeAdded modified event. |
