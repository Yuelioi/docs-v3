---
display_name: Save Packages with Dialog
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Editor Loading And Saving](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/EditorLoadingAndSaving)

Save all packages. Optionally prompting the user to select which packages to save.
Prompt the user to select which dirty packages to save and check them out from source control (if enabled).

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
