---
display_name: Get Curve Value with Default
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Curves](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Curves)

Returns whether a named curve was found, its value, and a default value when it's not found.

Target is Anim Instance

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | Curve Name | The name of the curve. |
| real | Default Value | Value to use when the curve is not found. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Out Value | The curve's value. |
| boolean | Return Value |  |
