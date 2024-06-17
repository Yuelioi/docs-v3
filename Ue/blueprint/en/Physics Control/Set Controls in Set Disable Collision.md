---
title: Set Controls in Set Disable Collision
order: 120
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Set | The set of controls to modify. Standard sets will include "All", "WorldSpace", "ParentSpace" and things like "WorldSpace-ArmLeft", depending on how controls have been created. |
| boolean | Disable Collision | If set then the control will disable collision between the bodies it connects. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
