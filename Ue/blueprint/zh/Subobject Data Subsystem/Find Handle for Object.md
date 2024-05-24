---
display_name: Find Handle for Object
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Subobject Data Subsystem](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SubobjectDataSubsystem)

Attempt to find an existing handle for the given object.

Target is Subobject Data Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Context | The context that the object to find is within |
| object | Object to Find | The object that you want to find the handle for within the context |
| object | BPContext |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | FSubobjectDataHandle The subobject handle for the object, Invalid handle if not found. |
