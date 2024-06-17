---
title: Append Rectangle Compatibility 5 0
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Compatibility](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Compatibility)

5.0 Preview 1 Compatibility version of AppendRectangleXY. Incorrectly interprets the input dimensions.
Incorrectly divides the input DimensionX and DimensionY by 2.
@warning It is strongly recommended that callers of this function update to the current AppendRectangleXY function!

Target is Geometry Script Library Mesh Primitive Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Primitive Options |  |
| transform | Transform |  |
| real | Dimension X |  |
| real | Dimension Y |  |
| integer | Steps Width |  |
| integer | Steps Height |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | 5.0 Preview 1 Compatibility version of AppendRectangleXY. Incorrectly interprets the input dimensions.Incorrectly divides the input DimensionX and DimensionY by 2.@warning It is strongly recommended that callers of this function update to the current AppendRectangleXY function! |
