---
display_name: Transform to Bone Space
order: 42
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Skinned Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/SkinnedMesh)

Transform a location/rotation from world space to bone relative space.
This is handy if you know the location in world space for a bone attachment, as AttachComponent takes location/rotation in bone-relative space.

Target is Skinned Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | Bone Name | Name of bone |
| vector | In Position | Input position |
| rotator | In Rotation | Input rotation |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Out Position | (out) Transformed position |
| rotator | Out Rotation | (out) Transformed rotation |
