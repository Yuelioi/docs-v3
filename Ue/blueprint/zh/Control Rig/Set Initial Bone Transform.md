---
display_name: Set Initial Bone Transform
order: 37
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Control Rig](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ControlRig_1)

Sets the initial transform of the bone in the requested space

Target is Control Rig Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Bone Name | The name of the bone to set the transform for |
| transform | Initial Transform | The initial transform to set for the bone |
| enum | Space | The space to set the transform in |
| boolean | Propagate to Children | If true the child bones will be moved together with the affected bone |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
