---
display_name: VInterp To
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Interpolation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Interpolation)

Tries to reach Target based on distance from Current position, giving a nice smooth feeling when tracking a position.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Current | Actual position |
| vector | Target | Target position |
| real | Delta Time | Time since last tick |
| real | Interp Speed | Interpolation speed, if the speed given is 0, then jump to the target. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value | New interpolated position |
