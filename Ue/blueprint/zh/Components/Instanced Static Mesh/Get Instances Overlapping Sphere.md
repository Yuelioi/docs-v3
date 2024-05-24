---
display_name: Get Instances Overlapping Sphere
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Instanced Static Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/InstancedStaticMesh)

Returns the instances with instance bounds overlapping the specified sphere. The return value is an array of instance indices.

Target is Instanced Static Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| vector | Center |  |
| real | Radius |  |
| boolean | Sphere in World Space |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Return Value | Returns the instances with instance bounds overlapping the specified sphere. The return value is an array of instance indices. |
