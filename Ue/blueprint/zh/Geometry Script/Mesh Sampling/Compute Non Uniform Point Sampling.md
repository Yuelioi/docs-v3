---
display_name: Compute Non Uniform Point Sampling
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Sampling](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshSampling)

Compute a set of sample points lying on the surface of TargetMesh based on the provided sampling Options and NonUniformOptions.
The sample points have radii in the range \[Options.SamplingRadius, NonUniformOptions.MaxSamplingRadius\], and
are non-overlapping, ie the distance between two points is always larger than the sum of their respective radii.

Target is Geometry Script Library Mesh Sampling Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Options |  |
| struct | Non Uniform Options |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| transform | Samples |  |
| real | Sample Radii |  |
| struct | Triangle IDs |  |
| object | Target Mesh | Compute a set of sample points lying on the surface of TargetMesh based on the provided sampling Options and NonUniformOptions.The sample points have radii in the range \[Options.SamplingRadius, NonUniformOptions.MaxSamplingRadius\], andare non-overlapping, ie the distance between two points is always larger than the sum of their respective radii. |
