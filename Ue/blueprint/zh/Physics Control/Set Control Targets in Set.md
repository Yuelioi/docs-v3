---
display_name: Set Control Targets in Set
order: 114
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Modifies existing control targets - i.e. what they are driving towards, relative to the parent objects

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Set | The set of controls to modify. Standard sets will include "All", "WorldSpace", "ParentSpace" and things like "WorldSpace-ArmLeft", depending on how controls have been created. |
| struct | Control Target | The new target for the controls |
| boolean | Enable Control | Enables the controls if currently disabled |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
