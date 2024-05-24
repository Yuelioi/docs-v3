---
display_name: Add Selected Actors to Layer
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Layers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Layers)

Adds selected actors to the named layer.

Target is Layers Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Layer Name | A layer name. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if at least one actor was added. false is returned if all selected actors already belong to the named layer. |
