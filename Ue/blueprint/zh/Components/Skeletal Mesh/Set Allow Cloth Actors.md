---
title: Set Allow Cloth Actors
order: 21
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Skeletal Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/SkeletalMesh)

Sets whether cloth assets should be created/simulated in this component.
This will update the conditional flag and you will want to call RecreateClothingActors for it to take effect.

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | In Allow | Whether to allow the creation of cloth assets and simulation. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
