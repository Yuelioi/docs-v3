---
title: Set Control Sparse Datas in Set
order: 95
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Modifies existing control data - i.e. the strengths etc of the controls driving towards the targets

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Set | The set of controls to update. Standard sets will include "All", "WorldSpace", "ParentSpace" and things like "WorldSpace-ArmLeft", depending on how controls have been created. |
| struct | Control Data | The new control data |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
