---
display_name: Upgrade Operator Nodes
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Blueprint Upgrade Tools](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/BlueprintUpgradeTools)

Replace any old operator nodes (float + float, vector + float, int + vector, etc)
with the newer Promotable Operator version of the node. Preserve any connections the
original node had to the newer version of the node.

Target is Blueprint Editor Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Blueprint | Blueprint to upgrade |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
