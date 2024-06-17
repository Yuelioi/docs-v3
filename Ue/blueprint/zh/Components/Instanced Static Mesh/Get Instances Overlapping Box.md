---
title: Get Instances Overlapping Box
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Instanced Static Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/InstancedStaticMesh)

Returns the instances with instance bounds overlapping the specified box. The return value is an array of instance indices.

Target is Instanced Static Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Box |  |
| boolean | Box in World Space |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Return Value | Returns the instances with instance bounds overlapping the specified box. The return value is an array of instance indices. |
