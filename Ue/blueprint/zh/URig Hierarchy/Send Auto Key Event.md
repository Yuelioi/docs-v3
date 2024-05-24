---
display_name: Send Auto Key Event
order: 120
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchy)

Sends an autokey event from the hierarchy to the world

Target is Rig Hierarchy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | In Element | The element to send the autokey for |
| real | In Offset in Seconds | The time offset in seconds |
| boolean | Asynchronous | If set to true the event will go on a thread safe queue |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
