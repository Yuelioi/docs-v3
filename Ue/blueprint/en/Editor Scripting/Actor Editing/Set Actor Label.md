---
display_name: Set Actor Label
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Actor Editing](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/ActorEditing)

Assigns a new label to this actor. Actor labels are only available in development builds.

Target is Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | New Actor Label | The new label string to assign to the actor. If empty, the actor will have a default label. |
| boolean | Mark Dirty | If true the actor's package will be marked dirty for saving. Otherwise it will not be. You should pass false for this parameter if dirtying is not allowed (like during loads) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
