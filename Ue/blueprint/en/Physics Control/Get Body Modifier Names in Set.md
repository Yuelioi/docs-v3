---
display_name: Get Body Modifier Names in Set
order: 29
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Returns a reference to all the body modifier names that have been created and are in the specified
set, which could be a limb, or a subsequently created set. Standard sets will include "All" and things like
"ArmLeft", depending on how body modifiers have been created.

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | Set |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| name | Return Value | Returns a reference to all the body modifier names that have been created and are in the specifiedset, which could be a limb, or a subsequently created set. Standard sets will include "All" and things like"ArmLeft", depending on how body modifiers have been created. |
