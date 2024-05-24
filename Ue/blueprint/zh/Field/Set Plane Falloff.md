---
display_name: Set Plane Falloff
order: 23
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Field](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Field)

Plane scalar field that will be defined only within a distance from a plane

Target is Plane Falloff

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| real | Field Magnitude | Magnitude of the plane falloff field |
| real | Min Range | The initial function value between 0 and 1 will be scaled between MinRange and MaxRange before being multiplied by magnitude |
| real | Max Range | The initial function value between 0 and 1 will be scaled between MinRange and MaxRange before being multiplied by magnitude |
| real | Default Value | The field value will be set to default if the sample projected distance ((Sample Position - Center Position).dot(Plane Normal)) is higher than the Plane Distance |
| real | Plane Distance | Distance limit for the plane falloff field starting from the center position and extending in the direction of the plane normal |
| vector | Center Position | Plane center position of the plane falloff field |
| vector | Plane Normal | Plane normal of the plane falloff field |
| enum | Falloff Type | Type of falloff function used to model the evolution of the field from the plane surface to the distance isosurface |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value |  |
