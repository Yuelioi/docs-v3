---
display_name: Locate Bound Objects
order: 67
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Sequence](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Sequence)

Locate all the objects that correspond to the specified object ID, using the specified context

Target is Movie Scene Sequence Extensions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Sequence | The sequence to locate bound objects for |
| struct | In Binding | The object binding |
| object | Context | Optional context to use to find the required object |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | An array of all bound objects |
