---
title: Create Controls from Skeletal Mesh and Constraint Profile
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Creates a collection of ParentSpace controls controlling a skeletal mesh, initializing them
with a constraint profile

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Skeletal Mesh Component | The skeletal mesh which will have controls |
| name | Bone Names | The names of bones for which controls should be created. Each bone will be the child in a control |
| name | Constraint Profile | The constraint profile to use for initializing the control strength and damping (etc) parameters. Note that the controls will all be created in " parent space" - i.e. with each part controlled relative to its parent. The strength and damping will be taken from the values that the relevant joint in the physics asset would have given the constraint profile (or the default profile if it can't be found) - though they will not match exactly if the linear drive and different x/y/z values, or if the angular drive was using twist/swing instead of slerp. Note also that the joint constraints do not use the animation velocity as a target, so when creating controls in this way the control will set the skeletal animation velocity multiplier to zero. |
| name | Set | Which set to include the control in (optional). Note that it automatically gets added to the set "All" |
| boolean | Enabled | If true then the control will be enabled immediately. If false you will need to call SetControlEnabled(true) in order to enable it. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| name | Return Value | An array of the controls that have been created |
