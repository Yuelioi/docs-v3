---
display_name: Change Subobject Class
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Subobject Data Subsystem](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SubobjectDataSubsystem)

Attempts to change the subclass of a native component

Target is Subobject Data Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Handle | Handle to the subobject to change class of |
| class | New Class | The new class that is desired for the given subobject |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the class change was successful, false otherwise. |
