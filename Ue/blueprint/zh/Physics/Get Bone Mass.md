---
title: Get Bone Mass
order: 67
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Returns the mass (in kg) of the given bone

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | Bone Name | Name of the body to return. 'None' indicates root body. |
| boolean | Scale Mass | If true, the mass is scaled by the bone's MassScale. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value |  |
