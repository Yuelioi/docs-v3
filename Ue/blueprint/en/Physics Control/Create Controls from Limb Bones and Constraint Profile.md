---
display_name: Create Controls from Limb Bones and Constraint Profile
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Creates a collection of ParentSpace controls controlling a skeletal mesh, grouped together in limbs, initializing
them with a constraint profile

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Limb Bones | A map relating the limbs and the bones that they contain. Typically create this using GetLimbBonesFromSkeletalMesh |
| name | Constraint Profile | The constraint profile to use for initializing the control strength and damping (etc) parameters. Note that the controls will all be created in " parent space" - i.e. with each part controlled relative to its parent. The strength and damping will be taken from the values that the relevant joint in the physics asset would have given the constraint profile (or the default profile if it can't be found) - though they will not match exactly if the linear drive and different x/y/z values, or if the angular drive was using twist/swing instead of slerp. Note also that the joint constraints do not use the animation velocity as a target, so when creating controls in this way the control will set the skeletal animation velocity multiplier to zero. |
| boolean | Enabled | If true then the control will be enabled immediately. If false you will need to call SetControlEnabled(true) in order to enable it. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | All Controls | A single container for all the controls that have been created |
| name | Return Value | A map containing the controls for each limb |
