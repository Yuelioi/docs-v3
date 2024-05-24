---
display_name: Override Animation Data
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/Animation)

This overrides current AnimationData parameter in the SkeletalMeshComponent. This will serialize when the component serialize
so it can be used during construction script. However note that this will override current existing data
This can be useful if you'd like to make a blueprint with custom default animation per component
This sets single player mode, which means you can't use AnimBlueprint with it

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Anim to Play |  |
| boolean | Is Looping |  |
| boolean | Is Playing |  |
| real | Position |  |
| real | Play Rate |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
