---
display_name: Vector 4 Mirror by Vector 3
order: 23
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Vector 4](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Vector4)

Given a direction vector and a surface normal, returns the vector reflected across the surface normal.
Produces a result like shining a laser at a mirror!
The W element is ignored.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Direction | Direction vector the ray is coming from. |
| struct | Surface Normal | A normal of the surface the ray should be reflected on. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Reflected vector. |
