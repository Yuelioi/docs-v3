---
display_name: Set Angular Limits
order: 25
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Sets the Angular Motion Ranges for a named constraint

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Bone Name | Name of bone to adjust constraint ranges for |
| real | Swing 1Limit Angle | Size of limit in degrees, 0 means locked, 180 means free |
| real | Twist Limit Angle | Size of limit in degrees, 0 means locked, 180 means free |
| real | Swing 2Limit Angle | Size of limit in degrees, 0 means locked, 180 means free |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
