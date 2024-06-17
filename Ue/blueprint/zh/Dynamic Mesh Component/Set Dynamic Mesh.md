---
title: Set Dynamic Mesh
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dynamic Mesh Component](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DynamicMeshComponent)

Replace the current UDynamicMesh with a new one, and transfer ownership of NewMesh to this Component.
This can be used to (eg) assign a UDynamicMesh created with NewObject in the Transient Package to this Component.
@warning If NewMesh is owned/Outer'd to another DynamicMeshComponent, a GLEO error may occur if that Component is serialized.

Target is Dynamic Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | New Mesh |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
