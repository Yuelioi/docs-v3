---
title: Set Control Sparse Datas
order: 96
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
| name | Names | The names of the controls to update. Note that if you have these in a FPhysicsControlNameArray then it can be split. |
| struct | Control Data | The new control data |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
