---
display_name: Get Scaled Capsule Size Without Hemisphere
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Capsule](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/Capsule)

Returns the capsule radius and half-height scaled by the component scale. Half-height excludes the hemisphere end cap.

Target is Capsule Collision

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Out Radius | Radius of the capsule, ignoring component scaling. |
| real | Out Half Height Without Hemisphere | Half-height of the capsule, scaled by the component scale. Excludes the hemisphere end cap. |
