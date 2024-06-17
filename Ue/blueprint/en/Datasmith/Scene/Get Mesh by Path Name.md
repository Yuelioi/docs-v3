---
title: Get Mesh by Path Name
order: 30
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Datasmith](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Datasmith) > [Scene](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Datasmith/Scene)

Find in the Datasmith scene the MeshElement that correspond to the mesh path name.
The function will return an invalid MeshElement, if the MeshPathName is empty or if it's not relative to the Datasmith scene or if it's not found.

Target is Datasmith Scene Element Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Mesh Path Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Find in the Datasmith scene the MeshElement that correspond to the mesh path name.The function will return an invalid MeshElement, if the MeshPathName is empty or if it's not relative to the Datasmith scene or if it's not found. |
