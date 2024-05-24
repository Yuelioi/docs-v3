---
display_name: Interpolate Material Instance Parameters
order: 33
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rendering](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering) > [Material](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Rendering/Material)

Interpolates the scalar and vector parameters of this material instance based on two other material instances, and an alpha blending factor
The output is the object itself (this).
Supports the case SourceA==this || SourceB==this
Both material have to be from the same base material

Target is Material Instance Dynamic

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Source A | value that is used for Alpha=0, silently ignores the case if 0 |
| object | Source B | value that is used for Alpha=1, silently ignores the case if 0 |
| real | Alpha | usually in the range 0..1, values outside the range extrapolate |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
