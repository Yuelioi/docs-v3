---
display_name: Get Patch to World Transform
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Landscape Patch](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LandscapePatch)

Gets the transform from patch to world. The transform is based off of the component
transform, but with rotation changed to align to the landscape, only using the yaw
to rotate it relative to the landscape.

Target is Landscape Texture Patch

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Return Value | Gets the transform from patch to world. The transform is based off of the componenttransform, but with rotation changed to align to the landscape, only using the yawto rotate it relative to the landscape. |
