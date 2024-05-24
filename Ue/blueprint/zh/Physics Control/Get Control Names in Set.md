---
display_name: Get Control Names in Set
order: 44
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Returns a reference to all the control names that have been created and are in the specified
set, which could be a limb, or a subsequently created set. Standard sets will include "All", "WorldSpace",
"ParentSpace" and things like "WorldSpace-ArmLeft", depending on how controls have been created.

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | Set |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| name | Return Value | Returns a reference to all the control names that have been created and are in the specifiedset, which could be a limb, or a subsequently created set. Standard sets will include "All", "WorldSpace","ParentSpace" and things like "WorldSpace-ArmLeft", depending on how controls have been created. |
