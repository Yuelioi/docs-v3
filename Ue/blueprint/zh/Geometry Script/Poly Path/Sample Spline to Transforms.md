---
display_name: Sample Spline to Transforms
order: 21
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Poly Path](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PolyPath)

Sample a USplineComponent into a list of FTransforms, based on the given SamplingOptions.

Target is Geometry Script Library Poly Path Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Spline |  |
| struct | Sampling Options |  |
| transform | Relative Transform | a constant Transform applied to each sample Transform in its local frame of reference. So, eg, an X Rotation will rotate each frame around the local spline Tangent vector |
| boolean | Include Scale | if true, the Scale of each FTransform is taken from the Spline, otherwise the Transforms have unit scale |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| transform | Frames | Transforms are returned here, with X axis oriented along spline Tangent and Z as the 'Up' vector. |
| real | Frame Times | the spline Time value used for each Frame. Note the Times Use Constant Velocity output indicates whether these times are w.r.t. to a constant-speed parameterization of the spline. |
| boolean | Times Use Constant Velocity | whether the FrameTimes are w.r.t. a 'constant speed' traversal of the spline |
