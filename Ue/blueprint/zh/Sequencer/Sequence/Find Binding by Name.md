---
display_name: Find Binding by Name
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Sequence](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Sequence)

Attempt to locate a binding in this sequence by its name

Target is Movie Scene Sequence Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Sequence | The sequence within which to find the binding |
| string | Name | The display name of the binding to look up |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | A unique identifier for the binding, or invalid |
