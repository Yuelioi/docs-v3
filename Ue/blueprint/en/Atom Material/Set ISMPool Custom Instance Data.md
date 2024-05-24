---
display_name: Set ISMPool Custom Instance Data
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Atom Material](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AtomMaterial)

Set a custom instance data value for all instances associated with a geometry collection.
This assumes that the geometry collection is using a custom instanced renderer.

Target is Geometry Collection Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Geometry Collection Component | The Geometry Collection Component that we want to set custom instance data on. |
| integer | Custom Data Index | The custom instance data slot that we want to set. |
| real | Custom Data Value | The value to set to the custom instance data slot. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
