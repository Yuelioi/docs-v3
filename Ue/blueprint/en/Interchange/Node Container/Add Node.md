---
display_name: Add Node
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Interchange](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Interchange) > [Node Container](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Interchange/NodeContainer)

Add a node to the container. The node is added into a TMap.

Target is Interchange Base Node Container

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Node | a pointer on the node you want to add |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Return Value | : return the node unique ID of the added item. If the node already exist it will return the existing ID. Return InvalidNodeUid if the node cannot be added. |
