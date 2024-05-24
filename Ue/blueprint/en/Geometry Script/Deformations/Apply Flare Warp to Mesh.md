---
display_name: Apply Flare Warp to Mesh
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Deformations](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Deformations)

Applies a Flare/Bulge warp around an axis defined by the Flare Orientation transform.
The amount of flare in the perpendicular directions can be controlled by FlarePercentX and FlarePercentY
and the extents of the affected region can be controlled by the Options.

Target is Geometry Script Library Mesh Deform Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Options |  |
| transform | Flare Orientation |  |
| real | Flare Percent X |  |
| real | Flare Percent Y |  |
| real | Flare Extent |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Applies a Flare/Bulge warp around an axis defined by the Flare Orientation transform.The amount of flare in the perpendicular directions can be controlled by FlarePercentX and FlarePercentYand the extents of the affected region can be controlled by the Options. |
