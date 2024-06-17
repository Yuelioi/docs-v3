---
title: Save Packages
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Editor Loading And Saving](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/EditorLoadingAndSaving)

Save all packages.
Assume all dirty packages should be saved and check out from source control (if enabled).

Target is Editor Loading and Saving Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Packages to Save | The list of packages to save. Both map and content packages are supported |
| boolean | Only Dirty |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true on success, false on fail. |
