---
display_name: To Quaternion (Vector4)
order: 24
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Conversions](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Conversions)

Return the Quaternion orientation corresponding to the direction in which the vector points.
Similar to the FRotator version, returns a result without roll such that it preserves the up vector.

Note: If you don't care about preserving the up vector and just want the most direct rotation, you can use the faster
'FindBetweenVectors(ForwardVector, YourVector)' or 'FindBetweenNormals(...)' if you know the vector is of unit length.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | In Vec |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Quaternion from the Vector's direction, without any roll. |
