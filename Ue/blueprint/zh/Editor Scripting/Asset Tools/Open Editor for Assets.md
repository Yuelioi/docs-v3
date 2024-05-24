---
display_name: Open Editor for Assets
order: 35
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Asset Tools](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/AssetTools)

Tries to open an editor for all of the specified assets.
If any of the assets are already open, it will not create a new editor for them.
If all assets are of the same type, the supporting AssetTypeAction (if it exists) is responsible for the details of how to handle opening multiple assets at once.

Target is Asset Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Assets |  |
| enum | Opened Method |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Tries to open an editor for all of the specified assets.If any of the assets are already open, it will not create a new editor for them.If all assets are of the same type, the supporting AssetTypeAction (if it exists) is responsible for the details of how to handle opening multiple assets at once. |
