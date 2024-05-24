---
display_name: Apply Math Warp to Mesh
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Deformations](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Deformations)

Applies various simple math-function-based warps around an axis defined by the Warp Orientation transform,
currently a 1D or 2D sine-wave with arbitrary orientation may be selected by WarpType.

Target is Geometry Script Library Mesh Deform Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| transform | Warp Orientation |  |
| enum | Warp Type |  |
| struct | Options |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Applies various simple math-function-based warps around an axis defined by the Warp Orientation transform,currently a 1D or 2D sine-wave with arbitrary orientation may be selected by WarpType. |
