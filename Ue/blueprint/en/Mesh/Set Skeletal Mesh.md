---
title: Set Skeletal Mesh
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Mesh)

Call this first to load the weights for a skeletal mesh for fast editing.

Target is Skin Weight Modifier

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Mesh | The skeletal mesh asset to load for weight editing |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | bool - true if the mesh weights were successfully loaded. |
