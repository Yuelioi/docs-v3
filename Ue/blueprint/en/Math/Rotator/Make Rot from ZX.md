---
display_name: Make Rot from ZX
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Rotator](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Rotator)

Builds a matrix with given Z and X axes. Z will remain fixed, X may be changed minimally to enforce orthogonality. Y will be computed. Inputs need not be normalized.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Z |  |
| vector | X |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| rotator | Return Value | Builds a matrix with given Z and X axes. Z will remain fixed, X may be changed minimally to enforce orthogonality. Y will be computed. Inputs need not be normalized. |
