---
title: Create New Geometry Cache Groom Binding Asset
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Groom](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Groom)

Create a new groom binding asset within the contents space of the project. The asset name will be auto generated based on the groom asset name and the skeletal asset name

Target is Groom Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Groom Asset | Groom asset for binding |
| object | Geometry Cache |  |
| integer | Num Interpolation Points | (Optional) Number of point used for RBF constraint |
| object | Source Geometry Cache for Transfer |  |
| integer | Matching Section |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |
