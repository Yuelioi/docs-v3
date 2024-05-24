---
display_name: Rotation From X Vector
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Conversions](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Conversions)

Return the FRotator orientation corresponding to the direction in which the vector points.
Sets Yaw and Pitch to the proper numbers, and sets Roll to zero because the roll can't be determined from a vector.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | In Vec |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| rotator | Return Value | FRotator from the Vector's direction, without any roll. |
