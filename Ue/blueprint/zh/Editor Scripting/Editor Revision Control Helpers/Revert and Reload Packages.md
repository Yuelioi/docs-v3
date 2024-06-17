---
title: Revert and Reload Packages
order: 22
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Editor Revision Control Helpers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/EditorRevisionControlHelpers)

Reverts the provided files then reloads packages.

Target is Source Control Helpers

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | In Packages to Revert | The packages to revert |
| boolean | Revert All | Whether to revert all files |
| boolean | Reload World | Reload the world |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if succeeded. |
