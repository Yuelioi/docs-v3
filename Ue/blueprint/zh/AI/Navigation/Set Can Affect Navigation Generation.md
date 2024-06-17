---
title: Set Can Affect Navigation Generation
order: 37
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI) > [Navigation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI/Navigation)

Use SetCanAffectNavigationGeneration to change this value at runtime.
Note that calling this function at runtime will result in any navigation change only if runtime navigation generation is enabled.

Target is Pawn

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | New Value |  |
| boolean | Force Update |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
