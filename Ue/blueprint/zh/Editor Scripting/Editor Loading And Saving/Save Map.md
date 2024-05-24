---
display_name: Save Map
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Editor Loading And Saving](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/EditorLoadingAndSaving)

Saves the specified map, returning true on success.

Target is Editor Loading and Saving Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | World | The world to save. |
| string | Asset Path | The valid content directory path and name for the asset. E.g "/Game/MyMap" |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the map was saved successfully. |
