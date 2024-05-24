---
display_name: Normalize (Quat)
order: 20
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Quat](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Quat)

Normalize this quaternion if it is large enough as compared to the supplied tolerance.
If it is too small then set it to the identity quaternion.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Q |  |
| real | Tolerance | Minimum squared length of quaternion for normalization. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
