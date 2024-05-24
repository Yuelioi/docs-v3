---
display_name: Create Controls from Skeletal Mesh Below
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Creates a collection of controls controlling a skeletal mesh

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Skeletal Mesh Component | The skeletal mesh which will have controls |
| name | Bone Name | The name of the bone below which controls should be created. Each bone will be the child in a control |
| boolean | Include Self | Whether or not to include BoneName when creating controls |
| enum | Control Type | What type of control to create. This determines what the parent will be for each control |
| struct | Control Data | Describes the initial strength etc of the new control |
| name | Set | Which set to include the control in (optional). Note that it automatically gets added to the set "All" |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| name | Return Value | An array of the controls that have been created |
