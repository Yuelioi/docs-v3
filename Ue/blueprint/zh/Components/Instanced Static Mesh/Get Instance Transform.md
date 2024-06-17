---
title: Get Instance Transform
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Instanced Static Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/InstancedStaticMesh)

Get the transform for the instance specified. Instance is returned in local space of this component unless bWorldSpace is set. Returns True on success.

Target is Instanced Static Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| integer | Instance Index |  |
| boolean | World Space |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Out Instance Transform |  |
| boolean | Return Value | Get the transform for the instance specified. Instance is returned in local space of this component unless bWorldSpace is set. Returns True on success. |
