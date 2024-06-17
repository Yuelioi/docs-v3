---
title: Downsample Points
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Point Set](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PointSet)

Find a subset of the given Points of a specified size.
Can optionally specify a priorty weighting and/or request uniform spacing for the downsampled points.
Note: Ordering of the result will balance:
(1) if weights are provided, higher weight points come earlier and
(2) if uniform spacing is requested, points will be ordered to have an octree-style coverage --
so the first 8 points will cover the 8 octants (where samples are available) and the subsequent points will progressively fill in the space

Target is Geometry Script Library Point Set Sampling Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Points |  |
| struct | Options |  |
| integer | Keep Num Points |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Downsampled Indices |  |
