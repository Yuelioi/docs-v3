---
title: Copy Properties to Static Mesh
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dynamic Mesh Actor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DynamicMeshActor)

Attempt to copy Actor Properties to a StaticMeshActor. Optionally copy DynamicMeshComponent material list to the StaticMeshComponent.
This function is useful when (eg) swapping from a DynamicMeshActor to a StaticMeshActor as it will allow
many configured Actor settings to be preserved (like assigned DataLayers, etc)

Target is Generated Dynamic Mesh Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Static Mesh Actor |  |
| boolean | Copy Component Materials |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
