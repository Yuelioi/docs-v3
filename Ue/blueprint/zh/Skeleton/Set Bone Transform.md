---
display_name: Set Bone Transform
order: 20
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Skeleton](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Skeleton)

Sets the bone the desired local transform

Target is Skeleton Modifier

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Bone Name | The new bone's name that needs to be moved. |
| transform | In New Transform | The new local transform in the bone's parent space. |
| boolean | Move Children | Propagate new transform to children |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | \\c true if the operation succeeded, false otherwise. |
