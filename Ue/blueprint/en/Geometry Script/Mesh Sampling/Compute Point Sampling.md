---
display_name: Compute Point Sampling
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Sampling](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshSampling)

Compute a set of sample points lying on the surface of TargetMesh based on the provided sampling Options.
Samples are approximately uniformly distributed, and non-overlapping relative to the provided Options.SamplingRadius,
ie the distance between any pair of samples if >= 2\*SamplingRadius.

Target is Geometry Script Library Mesh Sampling Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Options |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| transform | Samples | output list of sample points. Transform Location is sample position, Rotation orients Z with the triangle normal |
| struct | Triangle IDs | TriangleID that contains each sample point. Length is the same as Samples array. |
| object | Target Mesh |  |
