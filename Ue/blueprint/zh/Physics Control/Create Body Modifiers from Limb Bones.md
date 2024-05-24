---
display_name: Create Body Modifiers from Limb Bones
order: 6
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
| struct | Body Modifier Data | The initial properties of the modifier |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | All Body Modifiers |  |
| name | Return Value | A map containing the modifiers for each limb |
