---
display_name: Assign Physics Asset
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Skeletal Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/SkeletalMesh)

Assigns a PhysicsAsset to the given SkeletalMesh if it is compatible. Passing
nullptr / None as the physics asset will always succeed and will clear the
physics asset assignment for the target SkeletalMesh

Target is Skeletal Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh | The mesh to attempt to assign the PhysicsAsset to |
| object | Physics Asset | The physics asset to assign to the provided mesh (or nullptr/None) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Whether the physics asset was successfully assigned to the mesh |
