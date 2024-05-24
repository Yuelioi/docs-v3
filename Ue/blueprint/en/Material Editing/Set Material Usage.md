---
display_name: Set Material Usage
order: 55
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Material Editing](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MaterialEditing)

Enable a particular usage for the supplied material (e.g. SkeletalMesh, ParticleSprite etc)

Target is Material Editing Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Material | Material to change usage for |
| enum | Usage | New usage type to enable for this material |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Needs Recompile | Returned to indicate if material needs recompiling after this change |
| boolean | Return Value |  |
