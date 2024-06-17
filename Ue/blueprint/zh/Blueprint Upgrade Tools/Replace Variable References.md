---
title: Replace Variable References
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Blueprint Upgrade Tools](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/BlueprintUpgradeTools)

Replace any references of variables with the OldVarName to references of those with the NewVarName if possible

Target is Blueprint Editor Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Blueprint | Blueprint to replace the variable references on |
| name | Old Var Name | The variable you want replaced |
| name | New Var Name | The new variable that will be used in the old one's place |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
