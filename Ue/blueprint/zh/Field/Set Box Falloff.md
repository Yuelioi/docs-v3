---
display_name: Set Box Falloff
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Field](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Field)

Box scalar field that will be defined only within a box

Target is Box Falloff

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| real | Field Magnitude | Magnitude of the box falloff field |
| real | Min Range | The initial function value between 0 and 1 will be scaled between MinRange and MaxRange before being multiplied by magnitude |
| real | Max Range | The initial function value between 0 and 1 will be scaled between MinRange and MaxRange before being multiplied by magnitude |
| real | Default Value | The field value will be set to Default if the sample distance from the box is higher than the scale of the transform |
| transform | Box Transform | Translation, Rotation and Scale of the unit box |
| enum | Falloff Type | Type of falloff function used to model the evolution of the field from the box surface to the sample position |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value |  |
