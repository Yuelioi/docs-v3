---
display_name: Get Connection Point Target for Node
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Virtual Camera](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VirtualCamera_1) > [Hierarchies](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VirtualCamera_1/Hierarchies)

Gets the connection point the modifier is configured to be bound to, if any.
This function is optional to implement; it is valid for it to always return false.

Target is Modifier Hierarchy Rules

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | Group Name |  |
| object | Component |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Connection |  |
| boolean | Return Value | Whether there is a connection point configured for this hierarchy node. |
