---
title: Update Instance Transform
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Instanced Static Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/InstancedStaticMesh)

Update the transform for the instance specified.

Target is Instanced Static Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Instance Index | The index of the instance to update |
| transform | New Instance Transform | The new transform |
| boolean | World Space | If true, the new transform is interpreted as a World Space transform, otherwise it is interpreted as Local Space |
| boolean | Mark Render State Dirty | If true, the change should be visible immediately. If you are updating many instances you should only set this to true for the last instance. |
| boolean | Teleport | Whether or not the instance's physics should be moved normally, or teleported (moved instantly, ignoring velocity). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True on success. |
