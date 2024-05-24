---
display_name: Add Bone
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Skeleton](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Skeleton)

Creates a new bone in the skeleton hierarchy at desired transform

Target is Skeleton Modifier

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Bone Name | The new bone's name. |
| name | In Parent Name | The new bone parent's name. |
| transform | In Transform | The default local transform in the parent space. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | \\c true if the operation succeeded, false otherwise. |
