---
title: Register Object for Input
order: 24
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [XR Creative](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/XRCreative)

Registers the given object with the Avatar's Input Component

- This allows dynamic input bindings such as input events in blueprints to work correctly
- Note: Ensure you call UnregisterObjectForInput when you are finished with the object
- otherwise input events will still fire until GC actually destroys the object

Target is XRCreative Avatar

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Object | The object to register |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
