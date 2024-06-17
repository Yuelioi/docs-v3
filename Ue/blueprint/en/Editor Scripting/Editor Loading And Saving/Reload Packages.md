---
title: Reload Packages
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Editor Loading And Saving](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/EditorLoadingAndSaving)

Helper function that attempts to reload the specified top-level packages.

Target is Editor Loading and Saving Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Packages to Reload | The list of packages that should be reloaded |
| enum | Interaction Mode | Whether the function is allowed to ask the user questions (such as whether to reload dirty packages) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Out Any Packages Reloaded | True if the set of loaded packages was changed |
| text | Out Error Message | An error message specifying any problems with reloading packages |
