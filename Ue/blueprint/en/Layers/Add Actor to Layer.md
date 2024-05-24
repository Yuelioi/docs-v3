---
display_name: Add Actor to Layer
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Layers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Layers)

Adds the actor to the named layer.

Target is Layers Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Actor | The actor to add to the named layer |
| name | Layer Name | The name of the layer to add the actor to |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the actor was added. false is returned if the actor already belongs to the layer. |
