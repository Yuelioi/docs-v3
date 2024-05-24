---
display_name: Duplicate Actors
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Level Utility](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/LevelUtility)

Duplicate actors from the world editor.

Target is Editor Actor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Actors to Duplicate | Actors to duplicate. |
| object | To World | World to place the duplicated actors in. * |
| vector | Offset | Translation to offset duplicated actors by. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The duplicated actors, or empty if it didn't succeed |
