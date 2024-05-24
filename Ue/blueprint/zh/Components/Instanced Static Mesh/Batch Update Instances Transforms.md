---
display_name: Batch Update Instances Transforms
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Instanced Static Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/InstancedStaticMesh)

Update the transform for an array of instances.

Target is Instanced Static Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Start Instance Index | The starting index of the instances to update |
| transform | New Instances Transforms | The new transforms |
| boolean | World Space | If true, the new transforms are interpreted as a World Space transform, otherwise it is interpreted as Local Space |
| boolean | Mark Render State Dirty | If true, the change should be visible immediately. If you are updating many instances you should only set this to true for the last instance. |
| boolean | Teleport | Whether or not the instances physics should be moved normally, or teleported (moved instantly, ignoring velocity). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True on success. |
