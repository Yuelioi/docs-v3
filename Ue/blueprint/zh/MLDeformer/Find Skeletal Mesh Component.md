---
title: Find Skeletal Mesh Component
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [MLDeformer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MLDeformer)

Find the skeletal mesh component to apply the deformer on.
This will return the skeletal mesh component (on this actor) which uses the same skeletal mesh as the passed in ML Deformer asset was trained on.
If there is no such skeletal mesh component then it will return a nullptr.

Target is MLDeformer Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| object | Asset | The ML Deformer asset to search a component for. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | The skeletal mesh component that would be the best. |
