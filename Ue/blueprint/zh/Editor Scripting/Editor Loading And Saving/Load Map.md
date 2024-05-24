---
display_name: Load Map
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Editor Loading And Saving](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/EditorLoadingAndSaving)

Loads the specified map. Does not prompt the user to save the current map.

Target is Editor Loading and Saving Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Filename | Level package filename, including path. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | true if the map was loaded successfully. |
