---
display_name: Find Closest Bone
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Skinned Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/SkinnedMesh)

finds the closest bone to the given location

Target is Skinned Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| vector | Test Location | the location to test against |
| real | Ignore Scale | (optional) if specified, only bones with scaling larger than the specified factor are considered |
| boolean | Require Physics Asset | (optional) if true, only bones with physics will be considered |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Bone Location | (optional, out) if specified, set to the world space location of the bone that was found, or (0,0,0) if no bone was found |
| name | Return Value | the name of the bone that was found, or 'None' if no bone was found |
