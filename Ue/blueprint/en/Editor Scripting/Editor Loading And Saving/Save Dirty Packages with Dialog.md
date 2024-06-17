---
title: Save Dirty Packages with Dialog
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Editor Loading And Saving](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/EditorLoadingAndSaving)

Looks at all currently loaded packages and saves them if their "bDirty" flag is set.
Prompt the user to select which dirty packages to save and check them out from source control (if enabled).

Target is Editor Loading and Saving Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| boolean | Save Map Packages | true if map packages should be saved |
| boolean | Save Content Packages | true if we should save content packages. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true on success, false on fail. |
