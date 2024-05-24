---
display_name: GetBoundObjectForSequencer
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer)

Retrieve the bound object that this interface wants to animate. Could be 'this' or a transient child object.

Target is Movie Scene Bound Object Proxy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| object | Resolved Object |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Pointer to the object that should be animated, or nullptr if it's not valid. |
