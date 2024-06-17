---
title: Create Controls from Limb Bones
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Creates a collection of controls controlling a skeletal mesh, grouped together in limbs

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Limb Bones | A map relating the limbs and the bones that they contain. Typically create this using GetLimbBonesFromSkeletalMesh |
| enum | Control Type | What type of control to create. This determines what the parent will be for each control |
| struct | Control Data | Describes the initial strength etc of the new control |
| object | World Component | Optional component to use as the parent object for any "world-space" controls that are created. Will be ignored if the controls being created are not world-space. |
| name | World Bone Name | Additional bone name to identify the world object if the WorldComponent is actually a skeletal mesh component. |
| string | Name Prefix | Optional string that is prefixed to each control that is created. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | All Controls | A single container for all the controls that have been created |
| name | Return Value | A map containing the controls for each limb |
