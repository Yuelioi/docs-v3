---
display_name: Remove Actor from Layer
order: 28
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Layers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Layers)

Removes an actor from the specified layer.

Target is Layers Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Actor | The actor to remove from the provided layer |
| name | Layer to Remove | The name of the layer to remove the actor from |
| boolean | Update Stats |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the actor was removed from the layer. false is returned if the actor already belonged to the layer. |
