---
display_name: Spawn Actor from Class
order: 63
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Level Utility](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/LevelUtility)

Create an actor and place it in the world editor. Can be created from a Blueprint or a Class.
The actor will be created in the current level and will be selected.

Target is Editor Actor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| class | Actor Class | Asset to attempt to use for an actor to place. |
| vector | Location | Location of the new actor. |
| rotator | Rotation |  |
| boolean | Transient |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The created actor. |
