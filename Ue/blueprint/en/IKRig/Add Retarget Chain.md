---
display_name: Add Retarget Chain
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [IKRig](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/IKRig)

Add a new chain with the given Chain and Bone names. Returns newly created chain name (uniquified).
Note: only the ChainName is required here, all else can be set later.

Target is IKRig Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Chain Name |  |
| name | Start Bone Name |  |
| name | End Bone Name |  |
| name | Goal Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| name | Return Value | Add a new chain with the given Chain and Bone names. Returns newly created chain name (uniquified).Note: only the ChainName is required here, all else can be set later. |
