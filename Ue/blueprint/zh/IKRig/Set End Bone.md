---
display_name: Set End Bone
order: 41
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [IKRig](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/IKRig)

Set the end bone on a given solver. (not all solvers require extra end bones, checks CanSetEndBone() first)

Target is IKRig Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | End Bone Name |  |
| integer | Solver Index |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Set the end bone on a given solver. (not all solvers require extra end bones, checks CanSetEndBone() first) |
