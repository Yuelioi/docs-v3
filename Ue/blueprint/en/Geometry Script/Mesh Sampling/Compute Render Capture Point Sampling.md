---
display_name: Compute Render Capture Point Sampling
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Sampling](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshSampling)

Compute oriented sample points on the visible surfaces of the given Actors
The Samples are computed using Render Capture from the given virtual Cameras

Target is Geometry Script Library Mesh Sampling Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Actors |  |
| struct | Cameras |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| transform | Samples |  |
