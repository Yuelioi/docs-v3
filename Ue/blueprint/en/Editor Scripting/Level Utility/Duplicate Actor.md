---
display_name: Duplicate Actor
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Level Utility](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/LevelUtility)

Duplicate an actor from the world editor.

Target is Editor Actor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Actor to Duplicate | Actor to duplicate. |
| object | To World | World to place the duplicated actor in. |
| vector | Offset | Translation to offset duplicated actor by. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The duplicated actor, or none if it didn't succeed |
